# 📈 Optimización Comercial: Evaluación de Ventas y Desempeño de Productos

### 🎯 Objetivo del Proyecto
El objetivo principal es realizar un análisis exhaustivo de los datos de ventas históricos para proporcionar **insights estratégicos** que mejoren la toma de decisiones comerciales. Se busca identificar patrones de compra, detectar productos de bajo rendimiento y reconocer los mercados geográficos más rentables para la organización.

### ❓ Preguntas de Negocio Resueltas
A través del análisis de datos, dimos respuesta a las siguientes interrogantes clave:
1.  **¿Cuáles son los 5 productos estrella?**.
2.  **¿Qué productos tienen bajo rendimiento?**.
3.  **¿Qué países lideran las ventas?**.

### 🛠️ Tech Stack
* **Lenguaje:** Python 
* **Manipulación de Datos:** Pandas, Numpy.
* **Visualización:** Matplotlib, Seaborn.
* **Datos:** Dataset transaccional de ventas.

### 🔄 Metodología (Pipeline)

#### 1. Limpieza de Datos (Data Cleaning)
Se procesó el dataset original (2,823 registros, 25 columnas) para asegurar su integridad:
* **Manejo de Nulos:** Tratamiento de valores faltantes.
* **Selección de Variables:** Reducción de 25 a 21 columnas, eliminando datos irrelevantes para el análisis.
* **Saneamiento:** Eliminación de registros duplicados y validación de tipos de datos.

#### 2. Análisis Exploratorio (EDA)
Se aplicaron técnicas estadísticas y de agrupación para responder las preguntas de negocio:
* **Segmentación Pareto:** Identificación del 20% de productos que generan el 80% del volumen.
* **Análisis de Umbral:** Definición del percentil 25 para clasificar productos de "bajo rendimiento".

### 📊 Insights Clave
Tras el análisis, se destacan los siguientes hallazgos:

* **🏆 Top 5 Categorías más vendidas:**
    1.  **Classic Cars** (Líder indiscutible con >33k unidades).
    2.  Vintage Cars.
    3.  Motorcycles.
    4.  Trucks and Buses.
    5.  Planes.
* **🌍 Mercados:** Se identificaron los países con mayor volumen de facturación para focalizar campañas de marketing.

### 📂 Estructura del Repositorio
* `/Alcance_del_proyecto`: Definición de objetivos y KPIs.
* `/Analisis_de_datos`: Notebooks con el EDA y visualizaciones (`.ipynb`) y datasets procesados.
* `/Base_de_datos`: Archivos crudos (`sales_data.csv`).
* `/Limpieza de datos`: Scripts de preprocesamiento y ETL.

---
*Este proyecto forma parte de mi portafolio profesional como Analista de Datos.*

