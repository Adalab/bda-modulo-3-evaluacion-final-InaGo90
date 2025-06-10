# 🚀 Módulo 3: Evaluación Final - Análisis de Actividad de Clientes de Aerolínea 📊

¡Bienvenido/a al repositorio de mi evaluación final del Módulo 3 de Data Analytics! Aquí he aplicado los conocimientos adquiridos para desentrañar el comportamiento de los clientes de un programa de lealtad de una aerolínea.

Este proyecto ha sido una inmersión práctica en el ciclo de vida del análisis de datos, desde la limpieza inicial hasta la interpretación estadística.

## 📁 Estructura del Repositorio

* **`evaluacion-final.pdf`**: El enunciado oficial completo del ejercicio y los criterios de evaluación.
* **`1.2-bda-modulo-3-evaluacion-final-InaGo90.ipynb`**:
    * **Fase 1: Exploración y Limpieza de Datos.**
    * Este notebook es el punto de partida del análisis. Incluye la carga de los datos brutos, una primera inspección exploratoria y, crucialmente, la identificación y gestión de valores nulos para asegurar la integridad de los datos. El resultado de esta fase es un conjunto de datos limpio, listo para el análisis profundo.
* **`actividad_historial_clientes.csv`**:
    * Este archivo CSV es el **resultado directo de la fase de limpieza** realizada en el notebook `1.2-bda-modulo-3-evaluacion-final-InaGo90.ipynb`. Contiene el conjunto de datos limpio y transformado, listo para ser utilizado en las fases posteriores de visualización y análisis estadístico.
* **`2.2-bda-modulo-3-evaluacion-final-InaGo90.ipynb`**:
    * **Fase 2: Visualización de Datos.**
    * **Fase 3: Análisis Estadístico y Pruebas de Hipótesis.**
    * Aquí, los datos limpios cobran vida a través de visualizaciones perspicaces utilizando librerías como Matplotlib y Seaborn. Se exploran patrones y relaciones.
    * También se abordan los conceptos de estadística descriptiva e inferencial para extraer conclusiones significativas sobre el comportamiento del cliente.

## ✨ Puntos Destacados del Análisis

Durante el desarrollo de este proyecto, se han aplicado y fortalecido las siguientes habilidades y conceptos clave para un/a Data Analyst:

* **Preparación de Datos Robusta:** Desde la lectura eficiente de CSVs hasta la creación de DataFrames estructurados y listos para el análisis.
* **Gestión de Nulos:** Implementación de estrategias rigurosas para asegurar la integridad y calidad del conjunto de datos.
* **Visualización Efectiva de Datos:** Creación de gráficos claros y atractivos para comunicar insights de manera intuitiva, utilizando las capacidades de Matplotlib y Seaborn.
* **Estadística Descriptiva:** Cálculo de métricas fundamentales (media, desviación estándar, etc.) para resumir y entender las principales características de los datos.
* **Análisis de Agrupaciones (`groupby`):** Dominio de las operaciones de agregación y segmentación de datos para entender patrones de comportamiento por categorías (como el nivel educativo).
* **Comprensión Profunda de Métodos de Pandas:** Claridad en el uso de funciones como `len()` vs. `count()`, y cómo la inmutabilidad de tipos afecta operaciones como `.copy()`.
* **Manejo Avanzado de Fechas:** Conversión de formatos y extracción de información temporal (`datetime`) para análisis basados en el tiempo.

### 🧪 El Desafío de la Prueba de Hipótesis (Fase 3)

La parte final del ejercicio representó un desafío avanzado, centrado en la prueba de hipótesis para evaluar si existen diferencias significativas en el número de vuelos reservados por **múltiples niveles educativos**.

* **Objetivo:** Determinar la existencia de diferencias estadísticamente significativas entre los grupos de clientes con distintos niveles educativos en cuanto a sus vuelos reservados.
* **Enfoque y Aprendizaje Clave:** Se abordó la complejidad de aplicar pruebas de hipótesis a **más de dos grupos**. Esto implicó la adaptación de una función `prueba_hipotesis` para que pudiera manejar múltiples conjuntos de datos de forma flexible. El proceso incluyó:
    * **Verificación Dinámica de Normalidad:** Evaluando si cada grupo de datos sigue una distribución normal (con Shapiro-Wilk o Kolmogorov-Smirnov).
    * **Homogeneidad de Varianzas:** Determinando si las varianzas entre los grupos son similares (con Bartlett o Levene).
    * **
