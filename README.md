# Análisis de Datos: Los Mejores Juegos de PC en Metacritic 🎮📊

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-blue?style=for-the-badge&logo=pandas&logoColor=white)

## 📝 Descripción del Proyecto
Este proyecto consiste en un análisis exploratorio de datos (EDA) sobre un conjunto de datos que contiene información de más de 6,000 juegos de PC listados en Metacritic. El objetivo principal es transformar datos brutos en información valiosa sobre la calidad de los títulos a lo largo del tiempo y su relación con las clasificaciones por edad.

### 🎯 Pregunta Central del Análisis
> "¿Cuál es la evolución en el tiempo y la distribución del puntaje (score) de los mejores juegos de PC en Metacritic, y cómo se relaciona la clasificación de edad (Rating) con el puntaje promedio obtenido?"

## 🚀 Fases del Proyecto
El análisis se desarrolla en cuatro etapas clave:
1.  **Carga y Exploración:** Importación de datos e identificación de la estructura inicial (6,294 registros).
2.  **Limpieza y Transformación:** * Corrección de formatos numéricos en la columna `score`.
    * Tratamiento de fechas y extracción del año de lanzamiento.
    * Manejo de datos faltantes (imputación de 'N/A' en Ratings).
    * Unificación de categorías de Rating (ej. 'K-A' a 'E').
3.  **Análisis y Agregación:** * Cálculo de puntajes promedio por año y categoría.
    * Segmentación por calidad: Crítico (>=90), Excelente (80-89), Bueno (70-79), Regular (60-69) y Bajo (<60).
    * Análisis de correlación entre cantidad de juegos lanzados y calidad promedio.
4.  **Visualización:** Creación de histogramas y gráficos de barras para comunicar los hallazgos.

## 📊 Hallazgos Principales
* **Distribución de Calidad:** La mayor parte de los juegos analizados se encuentran en la categoría "Bueno" (70-79 puntos).
* **Tendencia Temporal:** Se observa una correlación negativa moderada (-0.58) entre la cantidad de juegos lanzados por año y el puntaje promedio, sugiriendo que en años con lanzamientos masivos, la calidad promedio tiende a diluirse.
* **Ratings:** Los juegos clasificados como **E10+** presentan, en promedio, puntajes ligeramente superiores a otras categorías.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python
* **Librerías:** * `Pandas`: Manipulación y limpieza de datos.
    * `NumPy`: Operaciones lógicas y matemáticas.
    * `Matplotlib` & `Seaborn`: Visualización estadística de datos.

## 📁 Estructura del Repositorio
* `TP_DATA_CHALLENGE.ipynb`: Notebook principal con todo el código y análisis.
* `metacritic_Toppc_games.csv`: Dataset utilizado para el estudio.
* `README.md`: Documentación del proyecto.

## ✒️ Autor
* **Sebastián Scorini** - [SebaScorini](https://github.com/SebaScorini)
