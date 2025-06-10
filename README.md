# 🚀 Módulo 3: Ejercicio de Evaluación Final - Análisis de Actividad de Clientes de Aerolínea 📊

¡Bienvenido/a al repositorio de mi evaluación final del Módulo 3 de Data Analytics! Aquí he tenido la oportunidad de aplicar los conocimientos adquiridos para explorar el comportamiento de los clientes de un programa de lealtad de una aerolínea.

Este proyecto ha sido una inmersión práctica en el ciclo de vida del análisis de datos, desde la preparación inicial hasta los intentos de inferencia estadística.

## 📁 Estructura del Repositorio

* **`evaluacion-final.pdf`**: El enunciado oficial del ejercicio, con todos los detalles y objetivos.
* **`1.2-bda-modulo-3-evaluacion-final-InaGo90.ipynb`**:
    * **Fase 1: Exploración y Limpieza de Datos.**
    * Este notebook marca el inicio del análisis. Aquí me he centrado en la carga de los datos brutos, una primera inspección para entender su estructura y la crucial tarea de identificar y gestionar valores nulos. El objetivo fue dejar el conjunto de datos preparado y lo más limpio posible para las siguientes etapas.
* **`actividad_historial_clientes.csv`**:
    * Este archivo CSV es el **resultado del proceso de limpieza y preparación** llevado a cabo en el notebook `1.2-bda-modulo-3-evaluacion-final-InaGo90.ipynb`. Es el conjunto de datos listo para ser utilizado en las fases de visualización y análisis estadístico.
* **`2.2-bda-modulo-3-evaluacion-final-InaGo90.ipynb`**:
    * **Fase 2: Visualización de Datos.**
    * **Fase 3: Análisis Estadístico y Pruebas de Hipótesis.**
    * En este notebook, los datos cobran vida a través de gráficos realizados con Matplotlib y Seaborn, buscando revelar patrones y tendencias.
    * También he abordado una aproximación a la estadística descriptiva e inferencial para intentar extraer conclusiones sobre el comportamiento del cliente.

## ✨ Puntos Clave y Aprendizajes Obtenidos

A lo largo de este proyecto, he tenido la oportunidad de poner en práctica y reforzar habilidades fundamentales para un/a Data Analyst:

* **Preparación de Datos:** Desde la carga de CSVs hasta la estructuración de DataFrames para un análisis efectivo.
* **Gestión de Nulos:** Aplicación de técnicas para asegurar la calidad e integridad del conjunto de datos.
* **Visualización de Datos:** Creación de gráficos explicativos para comunicar insights de forma clara, utilizando Matplotlib y Seaborn.
* **Estadística Descriptiva:** Cálculo de medidas esenciales (media, desviación estándar, etc.) para resumir y comprender las características principales de los datos.
* **Análisis por Agrupaciones (`groupby`):** Uso de operaciones de agregación para entender patrones de comportamiento segmentados por categorías (como el nivel educativo).
* **Profundización en Métodos de Pandas:** Claridad en el uso de funciones como `len()` vs. `count()`, y la comprensión de cómo la inmutabilidad de tipos afecta ciertas operaciones.
* **Manejo de Fechas:** Conversión de formatos y extracción de información temporal (`datetime`) para análisis basados en el tiempo.

### 🧪 El Desafío de la Prueba de Hipótesis (Fase 3)

La fase final del ejercicio, enfocada en una prueba de hipótesis para comparar el número de vuelos reservados por **múltiples niveles educativos**, representó un reto significativo y una valiosa curva de aprendizaje.

* **Objetivo:** Explorar si existen diferencias estadísticamente relevantes en el número de vuelos entre distintos grupos de clientes según su educación.
* **Proceso de Aprendizaje:** Tuve la oportunidad de trabajar en la adaptación de una función `prueba_hipotesis` para que pudiera manejar **más de dos grupos** de datos. Esto implicó comprender y aplicar la lógica para:
    * Evaluar la normalidad de cada grupo de datos (con tests como Shapiro-Wilk o Kolmogorov-Smirnov).
    * Determinar la homogeneidad de varianzas entre los grupos (con tests como Bartlett o Levene).
    * Seleccionar la prueba estadística adecuada para **múltiples grupos** (ANOVA o Kruskal-Wallis H) según las condiciones de normalidad y varianzas.
    * La preparación de los datos para la función fue clave, aprendiendo a extraer y pasar los conjuntos de datos numéricos de cada nivel educativo usando el operador de desempaquetado (`*args`).

Este ejercicio, especialmente en su fase final, fue un gran aprendizaje y me permitió profundizar en los conceptos de estadística inferencial aplicada con Python.

## 👩‍💻 Autor

Inés García Oubiña (Ina G. Oubiña)

---
