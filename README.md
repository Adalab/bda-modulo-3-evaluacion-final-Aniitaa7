# bda-modulo-3-evaluacion-final-Aniitaa7

# RESUMEN

Este proyecto está diseñado para realizar un análisis de datos sobre un conjunto de clientes, el cual está dividido en dos fases principales: **Exploración y Limpieza de Datos** y **Visualización de Datos**. El objetivo es obtener información relevante y patrones a partir de los datos, y luego visualizar esos hallazgos de manera comprensible.

## Fases del Proyecto

### 1. Fase 1: **Exploración y Limpieza de Datos**
En esta fase, nos enfocamos en explorar y limpiar el conjunto de datos para asegurarnos de que esté listo para su análisis y visualización. Las tareas realizadas incluyen:

#### a) **Cargar los Datos**
- Se cargaron los datos desde una fuente (puede ser un archivo CSV, base de datos, etc.) para comenzar con la exploración.

#### b) **Exploración Inicial**
- Se revisaron las primeras filas de los datos utilizando funciones como `head()`, `info()`, y `describe()` para tener una idea general del conjunto de datos.
- Se verificaron los tipos de datos, valores nulos, y valores fuera de rango.

#### c) **Limpieza de Datos**
- Se eliminaron las filas o columnas irrelevantes para el análisis.
- Se trataron los valores faltantes: eliminando, reemplazando o imputando según corresponda.
- Se transformaron las variables para que fueran más consistentes y útiles para el análisis, como cambiar valores negativos a positivos, etc.
- Se eliminaron duplicados y se manejaron las inconsistencias en los datos.

#### d) **Transformación de Datos**
- Se realizaron algunas transformaciones necesarias.

### 2. Fase 2: **Visualización de Datos**
En la fase de visualización, se aplicaron herramientas y técnicas gráficas para explorar patrones y relaciones dentro de los datos de manera visual. Las actividades realizadas incluyen:

#### a) **Clientes por Provincia/Estado**
- Un gráfico de barras mostró cómo se distribuyen los clientes según su ubicación geográfica, es decir, por provincia o estado.


#### b) **Relación entre Distancia de Vuelo y Puntos Acumulados**
- Se exploró si existe alguna correlación entre la distancia de los vuelos y los puntos acumulados por los clientes. Para ello, se utilizó un gráfico de dispersión (regplot) para visualizar esta relación, lo que permitió identificar tendencias o patrones.

#### c) **Distribución de Vuelos Reservados por Mes**
- Se creó un gráfico de barras para comparar la cantidad de vuelos reservados cada mes durante dos años (2017 y 2018). Esta visualización permitió observar cómo varió la actividad de los clientes a lo largo del tiempo.

#### d) **Proporción de Clientes por Tarjeta de Lealtad**
- Se realizó un gráfico circular para mostrar cómo se distribuyen los clientes según el tipo de tarjeta de fidelidad que poseen.

#### e) **Salario Promedio por Nivel Educativo**
- Se utilizó un gráfico de barras para comparar el salario promedio entre los diferentes niveles educativos de los clientes, lo que permitió visualizar las disparidades salariales según el nivel académico.

#### f) **Distribución de Clientes por Estado Civil y Género**
- Se utilizó un gráfico de barras para mostrar la distribución de los clientes según su género y estado civil. Esta visualización permitió observar la composición de los clientes en diferentes categorías.



# ABSTRACT

# Customer Data Analysis Project

This project is designed to perform an analysis on a customer dataset, which is divided into two main phases: **Data Exploration and Cleaning** and **Data Visualization**. The goal is to extract relevant insights and patterns from the data, and then visualize those findings in an understandable way.

## Project Phases

### 1. Phase 1: **Data Exploration and Cleaning**
In this phase, the focus was on exploring and cleaning the dataset to ensure it is ready for analysis and visualization. The tasks carried out include:

#### a) **Loading the Data**
- The data was loaded from a source (such as a CSV file, database, etc.) to begin the exploration process.

#### b) **Initial Exploration**
- The first few rows of the data were reviewed using functions like `head()`, `info()`, and `describe()` to get a general understanding of the dataset.
- The data types, null values, and out-of-range values were checked.

#### c) **Data Cleaning**
- Irrelevant rows or columns were removed from the dataset.
- Missing values were handled by either deleting, replacing, or imputing them as needed.
- Variables were transformed to make them more consistent and useful for analysis, such as changing negative values to positive, etc.
- Duplicates were removed and inconsistencies in the data were addressed.

#### d) **Data Transformation**
- Necessary transformations were carried out.
### 2. Phase 2: **Data Visualization**
In the visualization phase, graphical tools and techniques were applied to explore patterns and relationships within the data in a visual manner. The activities performed include:

#### a) **Clients by Province/State**
- A bar chart was created to show how clients are distributed according to their geographical location, i.e., by province or state.

#### b) **Relationship Between Flight Distance and Accumulated Points**
- The relationship between flight distance and the accumulated points by clients was explored. A scatter plot (regplot) was used to visualize this relationship, which helped identify trends or patterns.

#### c) **Monthly Flight Reservations Distribution**
- A bar chart was created to compare the number of flight reservations made each month in 2017 and 2018. This visualization helped observe how customer activity varied over time.

#### d) **Proportion of Clients by Loyalty Card**
- A pie chart was created to show how clients are distributed according to the type of loyalty card they hold.

#### e) **Average Salary by Educational Level**
- A bar chart was used to compare the average salary across different educational levels of the clients, allowing for the visualization of salary disparities based on academic level.

#### f) **Distribution of Clients by Marital Status and Gender**
- A bar chart was used to display the distribution of clients according to their gender and marital status. This visualization allowed for the observation of the composition of clients in different categories.



