# telecom-analysis
📊 ConnectaTel - Análisis Exploratorio de Datos (EDA)
📌 Descripción del proyecto

Este proyecto presenta un Análisis Exploratorio de Datos (EDA) sobre la información de clientes de ConnectaTel, una empresa de telecomunicaciones.

El objetivo fue evaluar la calidad de los datos, corregir inconsistencias, explorar el comportamiento de los usuarios y obtener insights que puedan apoyar la toma de decisiones comerciales mediante el uso de Python y sus principales librerías para análisis de datos.

## 🎯 Objetivos
Evaluar la calidad de los datos.
Identificar y corregir inconsistencias.
Preparar los datos para su análisis.
Explorar el comportamiento de los clientes mediante estadísticas descriptivas y visualizaciones.
Obtener conclusiones que apoyen futuras decisiones de negocio.
## 📁 Datasets

El análisis se realizó utilizando tres conjuntos de datos que contienen información complementaria sobre los clientes y los servicios de ConnectaTel.

Dataset	Descripción
users_latam.csv	Contiene la información demográfica de los clientes, incluyendo edad, ciudad de residencia, fecha de registro y el plan contratado.
plans.csv	Contiene las características de cada plan telefónico, como precio mensual, minutos incluidos, datos móviles (GB), mensajes incluidos y costo por excedentes.
usage.csv	Registra el uso real de los servicios por parte de los clientes, incluyendo duración de llamadas, cantidad de mensajes enviados y consumo de datos.
## 🛠️ Tecnologías utilizadas
Python
Pandas
NumPy
Matplotlib
Jupyter Notebook
# 🔍 Proceso de análisis
## 1. Exploración inicial

Se realizó una revisión general de los datos para identificar:

Tipos de datos.
Valores faltantes.
Registros duplicados.
Variables numéricas y categóricas.
Calidad general de la información.
## 2. Limpieza de datos

Durante esta etapa se corrigieron distintas inconsistencias presentes en la base de datos, entre ellas:

Edades inválidas.
Fechas con formatos incorrectos.
Valores faltantes.
Errores en variables categóricas.
Conversión de tipos de datos.
Validación de registros inconsistentes.
## 3. Análisis exploratorio

Posteriormente se exploraron las principales variables del conjunto de datos mediante estadísticas descriptivas y visualizaciones.

Se analizaron aspectos como:

Distribución de edades.
Duración de llamadas.
Uso de mensajes.
Consumo de datos.
Presencia de valores atípicos.
Comportamiento general de los clientes.
## 📈 Principales hallazgos
El segmento de adultos concentra la mayor parte de los clientes analizados.
La duración de las llamadas presenta una distribución relativamente estable, aunque existen usuarios con consumos significativamente superiores al promedio.
El uso de mensajes de texto está concentrado en un grupo reducido de clientes, mientras que la mayoría presenta un consumo bajo.
Los valores atípicos fueron conservados al representar comportamientos reales y no errores de captura.
La limpieza de los datos permitió mejorar la confiabilidad del análisis antes de generar conclusiones.
# 💡 Recomendaciones
Implementar validaciones automáticas para reducir errores en la captura de datos.
Diseñar estrategias comerciales enfocadas en el segmento con mayor representación dentro de la base de clientes.
Analizar a los usuarios de alto consumo para identificar oportunidades de fidelización o nuevos planes.
Mantener procesos periódicos de monitoreo y limpieza de datos para garantizar la calidad de la información.
## 📂 Estructura del proyecto
📦 ConnectaTel
│
├── data/
│   ├── users_latam.csv
│   ├── plans.csv
│   └── usage.csv
│
├── notebooks/
│   └── S7 Version-Estudiante-Project-ConnectaTel.ipynb
│
└── README.md
🚀 Conclusión

Este proyecto demuestra un flujo completo de Análisis Exploratorio de Datos (EDA), abarcando desde la inspección y limpieza de la información hasta la obtención de insights mediante técnicas de análisis descriptivo y visualización de datos.

El trabajo evidencia la importancia de una adecuada preparación de los datos antes de realizar cualquier análisis, permitiendo generar conclusiones más confiables y útiles para la toma de decisiones.
