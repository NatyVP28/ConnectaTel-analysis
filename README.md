**📊 Análisis de Datos — ConnectaTel**

Proyecto de análisis exploratorio y calidad de datos para la empresa ficticia ConnectaTel, desarrollado en Python utilizando Jupyter Notebook.

**🚀 Objetivo del proyecto**

El propósito de este proyecto es:

Explorar y comprender diferentes datasets de clientes y consumo.
Detectar problemas de calidad de datos.
Limpiar e imputar información faltante.
Analizar patrones de uso y comportamiento de usuarios.
Generar insights útiles para la toma de decisiones.

- Descripción de los datasets:
  
1. plans.csv

Contiene información sobre los planes disponibles para los usuarios.

Variables principales:
Tipo de plan
Precio
Beneficios incluidos
Límites de consumo

2. users_latam.csv

Información demográfica y general de los usuarios.

Variables principales:
user_id
Edad
Ciudad
País
Información de registro

3. usage.csv

Registra el consumo y comportamiento de uso de los clientes.

Variables principales:
Consumo de datos
Minutos utilizados
Mensajes enviados
Fechas de actividad
Etapas del análisis

🧩 Paso 1: Carga y exploración de datos

Se realizó:

Importación de librerías.
Carga de datasets.
Exploración inicial con:
.head()
.shape()
.info()
.describe()

Objetivo: Comprender la estructura y calidad inicial de los datos.

🧩 Paso 2: Calidad de datos
✔️ Revisión de valores nulos

Se identificaron columnas con valores faltantes y se evaluó:

Proporción de nulos.
Impacto sobre el análisis.
Posibles estrategias de imputación.

✔️ Detección de valores inválidos

Se identificaron valores sentinels y datos inconsistentes.

Ejemplo:

Valores -999 en la columna age fueron detectados como datos inválidos.

🧩 Paso 3: Limpieza y transformación

Durante esta etapa se realizaron tareas como:

Corrección de tipos de datos.
Eliminación de inconsistencias.
Tratamiento de nulos.
Normalización de información.
Preparación de datos para análisis.

🧩 Paso 4: Análisis exploratorio (EDA)

Se analizaron patrones y distribuciones utilizando visualizaciones.

Algunas preguntas abordadas:
¿Qué planes son más utilizados?
¿Cómo varía el consumo según la edad?
¿Existen diferencias entre países o regiones?
¿Qué usuarios presentan mayor consumo?
📈 Visualizaciones

- El notebook incluye gráficos como:

Histogramas
Boxplots
Gráficos de barras
Distribuciones
Heatmaps

Utilizando principalmente:

matplotlib
seaborn

**💡 Hallazgos principales**

Algunos hallazgos encontrados durante el análisis:

Existencia de valores sentinels en variables numéricas.
Presencia de valores faltantes en ciertos campos.
Diferencias de comportamiento entre segmentos de usuarios.
Patrones de consumo relevantes para el negocio.
