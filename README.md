# Evaluación Final del Módulo 3: Análisis del Comportamiento de Clientes en un Programa de Lealtad

## Autoría
Inés García Oubiña (Ina G. Oubiña)

## Descripción del Proyecto
Este repositorio contiene la resolución del ejercicio de evaluación final del Módulo 3 de un bootcamp de análisis de datos. El objetivo principal es analizar el comportamiento de los clientes dentro de un programa de lealtad de una aerolínea, utilizando dos conjuntos de datos que describen su actividad de vuelo.

El proyecto abarca las siguientes fases, aplicando diversas técnicas y herramientas de análisis de datos:
* **Análisis Exploratorio de Datos (EDA)**: Investigación inicial de los datos para descubrir patrones, detectar anomalías, probar hipótesis y verificar supuestos con la ayuda de estadísticas descriptivas y representaciones gráficas.
* **Gestión de Nulos**: Identificación y tratamiento de valores ausentes en los conjuntos de datos.
* **Visualización de Datos**: Creación de gráficos significativos utilizando `matplotlib` y `seaborn` para una mejor comprensión de los datos y la comunicación de hallazgos.
* **Estadística Descriptiva e Inferencial**: Aplicación de métodos estadísticos para resumir y describir características de los datos, así como para hacer inferencias sobre una población a partir de una muestra.

## Contenido del Repositorio

* `1.2-bda-modulo-3-evaluacion-final-InaGo90.ipynb`: Notebook de Jupyter que contiene la primera parte del análisis, incluyendo la exploración inicial de datos, limpieza y preprocesamiento.
* `2.2-bda-modulo-3-evaluacion-final-InaGo90.ipynb`: Notebook de Jupyter que continúa el análisis, probablemente enfocado en la aplicación de técnicas estadísticas y la generación de visualizaciones avanzadas.
* `actividad_historial_clientes.csv`: Archivo CSV que contiene información sobre la actividad de vuelo de los clientes, como el número de vuelos reservados, distancia volada, puntos acumulados y redimidos, y costos asociados.
* `evaluacion-final.pdf`: Documento PDF que describe los requisitos y criterios de evaluación para este ejercicio.

## Estructura de Datos Clave
Los datos se centran en el comportamiento de los clientes de una aerolínea y se dividen en dos archivos, que se unen para un análisis completo. Las variables principales incluyen:
* `Loyalty Number`: Identificador único para cada cliente.
* `Year`, `Month`: Información temporal de las actividades de vuelo.
* `Flights Booked`: Número total de vuelos reservados por el cliente.
* `Flights with Companions`: Vuelos reservados con acompañantes.
* `Total Flights`: Número total de vuelos realizados por el cliente.
* Otras variables relacionadas con puntos de lealtad (acumulados, redimidos) y costos asociados.

## Herramientas y Librerías
* Python
* `pandas`
* `numpy`
* `matplotlib.pyplot`
* `seaborn`
* `scipy.stats`
* `sklearn.impute.KNNImputer`
* `sklearn.preprocessing.StandardScaler`

## Criterios de Evaluación (Bootcamp)
Este ejercicio se evalúa en base a los siguientes criterios, considerados fundamentales para el análisis de datos:
* Análisis Exploratorio de los datos.
* Gestión de nulos.
* Visualización de datos con `matplotlib` y `seaborn`.
* Estadística descriptiva e inferencial.

Además, se consideran buenas prácticas en el código (comentarios, legibilidad, orden) y el uso de `git` con commits descriptivos.

---

Este README proporciona una visión general del proyecto, su propósito y los resultados esperados.
