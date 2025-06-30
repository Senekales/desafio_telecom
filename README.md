# 📊 Análisis de Abandono de Clientes (Churn) en TelecomX

¡Bienvenido al proyecto de análisis de abandono de clientes para TelecomX!

Este proyecto tiene como objetivo principal **identificar los factores clave que influyen en la renuncia de clientes** para ayudar al equipo de Data Science a desarrollar modelos predictivos y estrategias de retención efectivas.

---

## 🎯 Propósito del Proyecto

La empresa TelecomX está experimentando una alta tasa de abandono de clientes. Comprender por qué los clientes se van es crucial para implementar acciones que reduzcan esta pérdida y **retengan a los clientes existentes**.

Este análisis se enfoca en:

*   **Extracción y Carga (E):** Obtener los datos de origen.
*   **Transformación (T):** Limpiar, normalizar y preparar los datos para el análisis.
*   **Carga y Análisis (L):** Realizar un análisis exploratorio de datos (EDA) para descubrir patrones e insights.

El resultado de este análisis descriptivo servirá como base fundamental para futuros modelos de predicción de abandono.

---

## 📂 Estructura del Proyecto

El proyecto se encuentra estructurado en un cuaderno de Google Colab (`.ipynb`), que sigue las etapas del proceso ETL (Extract, Transform, Load) y Análisis:

1.  **Introducción:** Contexto del desafío y objetivo principal.
2.  **Extracción (E):** Importación de bibliotecas necesarias y carga del conjunto de datos desde una URL.
3.  **Transformación (T):**
    *   Normalización de los datos JSON anidados.
    *   Importación y revisión del diccionario de datos.
    *   Estandarización de nombres de columnas a español.
    *   Conocimiento del DataFrame (`.info()`, `.dtypes`).
    *   Manejo de inconsistencias (duplicados, valores vacíos/nulos, tipos de datos).
    *   Creación de nuevas columnas calculadas (`cuentas_diarias`).
4.  **Carga y Análisis (L):**
    *   Análisis descriptivo de los datos numéricos (`.describe()`).
    *   Importación de bibliotecas de visualización (Plotly).
    *   Construcción de histogramas para variables categóricas clave, visualizando la distribución por estado de renuncia.
    *   Creación de gráficos de línea para analizar la tasa de renuncia a lo largo del tiempo (meses de contrato).
    *   Generación de gráficos de dispersión para explorar relaciones entre variables numéricas coloreadas por el estado de renuncia.
    *   Creación de gráficos de caja para visualizar la distribución de variables numéricas por estado de renuncia.
5.  **Conclusiones:** Presentación de insights y recomendaciones clave basadas en el análisis visual.

---

## 🛠️ Instalación y Dependencias

Este proyecto está diseñado para ejecutarse en **Google Colab**, lo que simplifica la configuración del entorno. No se requiere instalación local de software adicional aparte de un navegador web.

Las principales bibliotecas de Python utilizadas, que ya están preinstaladas en el entorno de Google Colab, son:

*   `pandas`: Para manipulación y análisis de datos.
*   `requests`: Para obtener datos de URLs.
*   `json`: Para trabajar con datos en formato JSON.
*   `plotly`: Para la creación de visualizaciones interactivas.

Si por alguna razón necesitaras instalar alguna de estas bibliotecas en un entorno local o virtual, podrías usar pip.
