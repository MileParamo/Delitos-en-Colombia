# 📒 Uso de Cuadernos Jupyter
Este cuaderno de Jupyter proporciona un flujo de trabajo claro para realizar el análisis exploratorio y preparar los datos para análisis posteriores, asegurando la calidad y fiabilidad de la información utilizada.
## Introducción
En este cuaderno de Jupyter, se realiza un análisis exploratorio de un conjunto de datos que contiene información sobre delitos ocurridos en Colombia entre 2010 y 2023. El objetivo es evaluar la fiabilidad de la información y comprender los patrones delictivos a través de diversas transformaciones y validaciones de los datos. El análisis se lleva a cabo utilizando Python.
Este cuaderno sigue una serie de pasos, los cuales se detallan a continuación:
## 1.	Importación de Datos
En este primer paso, se importan los seis conjuntos de datos disponibles y se consolidan en una única base de datos. Esta base contiene las siguientes variables:
•	Id: Número de identificación único del registro.

•	Departamento: El departamento donde ocurrió el delito.

•	Municipio: El municipio donde ocurrió el delito.

•	Código DANE: Código DANE del lugar donde ocurrió el delito.

•	Armas Medio: Indica si se cuenta con acceso a armas.

•	Fecha: Fecha de ocurrencia del delito.

•	Género: Género del atacante.

•	Agrupaciones de edad: Edad del atacante.

•	Cantidad Del Delito: Número de delitos cometidos por el atacante.

•	Delito: Tipo de delito cometido.

•	ICON: Enlace a imágenes.

## 2. Asignación del Índice
El siguiente paso consiste en establecer la columna ID como el índice del conjunto de datos. Esto facilita las búsquedas y mejora la calidad del conjunto de datos, evitando duplicados o inconsistencias en los valores de identificación.
## 3. Revisión de los Tipos de Datos
En esta fase, se revisan los tipos de datos para asegurarse de que las columnas relevantes se manejen correctamente para análisis posteriores. Las columnas a mantener son: Departamento, Armas Medio, Género, Agrupaciones de edad, Delito, y Cantidad Del Delito.
## 4. Selección de Variables
En este paso, se seleccionan las columnas relevantes para el análisis y se identifican posibles errores de redacción en los valores de las columnas Género y Municipio. Además, se propone corregir los valores nulos en la columna Género, sustituyéndolos por la etiqueta "No Reportado" para reflejar la falta de información.
## 5. Valores Nulos y Corrección de Errores
Una vez identificados los valores nulos en varias columnas, se realizará una transformación para corregir estos datos y hacer que el conjunto sea más limpio y útil para el análisis. Este proceso incluye la corrección de valores atípicos y la modificación de datos mal escritos.
## 6. Conclusión
El objetivo de este análisis es proporcionar una visión general sobre la situación de los delitos en Colombia, identificar patrones delictivos y generar información útil para la toma de decisiones en políticas públicas y estrategias de seguridad. A través de este proceso, buscamos mejorar la comprensión sobre la delincuencia en el país y contribuir a la conciencia pública sobre este importante tema.
