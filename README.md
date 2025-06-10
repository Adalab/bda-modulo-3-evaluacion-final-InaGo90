# 🚀 Módulo 3: Ejercicio de Evaluación Final - Análisis de Actividad de Clientes de Aerolínea 📊

¡Bienvenida a mi repositorio de la evaluación final del Módulo 3 de Data Analytics! En este proyecto, he tenido la oportunidad de aplicar los conocimientos aprendidos para explorar el comportamiento de los clientes de un programa de lealtad de una aerolínea.

Este trabajo me ha permitido recorrer el ciclo de vida del análisis de datos, desde la preparación inicial hasta la interpretación de los datos.

## 📁 Estructura del Repositorio

* **`evaluacion-final.pdf`**: El enunciado oficial del ejercicio, donde se describen los objetivos y tareas.
* **`1.2-bda-modulo-3-evaluacion-final-InaGo90.ipynb`**:
    * **Fase 1: Exploración y Limpieza de Datos.**
    * Este notebook inicia el proceso de análisis. Aquí se realiza la carga de los datos, una primera exploración para entender su estructura y la importante tarea de identificar y gestionar valores nulos. El objetivo fue dejar el conjunto de datos preparado y lo más limpio posible para las fases siguientes.
* **`actividad_historial_clientes.csv`**:
    * Este archivo CSV es el **resultado de la fase de limpieza y preparación** llevada a cabo en el notebook `1.2-bda-modulo-3-evaluacion-final-InaGo90.ipynb`. Contiene el conjunto de datos limpio y transformado, listo para ser utilizado.
* **`2.2-bda-modulo-3-evaluacion-final-InaGo90.ipynb`**:
    * **Fase 2: Visualización de Datos.**
    * **Fase 3: Análisis Estadístico y Pruebas de Hipótesis.**
    * En este notebook, se utilizan librerías como Matplotlib y Seaborn para crear visualizaciones que ayudan a comprender los datos.
    * También se abordan conceptos de estadística descriptiva e inferencial para extraer conclusiones, incluyendo la realización de una prueba de hipótesis.

## ✨ Puntos Clave y Aprendizajes Obtenidos

A lo largo de este proyecto, he tenido la oportunidad de practicar y reforzar habilidades esenciales para un/a Data Analyst:

* **Preparación de Datos Robusta:** Desde la lectura de CSVs hasta la estructuración de DataFrames para un análisis efectivo.
* **Gestión de Nulos:** Implementación de técnicas para asegurar la calidad de los datos, tal como se aborda en el módulo `6. Nulos.ipynb`.
* **Visualización de Datos:** Creación de gráficos explicativos para comunicar información, utilizando Matplotlib y Seaborn.
* **Estadística Descriptiva:** Cálculo de medidas como la media, la desviación estándar y otras estadísticas clave, tal como se explora en el módulo `8.Estadística_Descriptiva.ipynb`.
* **Análisis por Agrupaciones (`groupby`):** Uso de operaciones de agregación para entender patrones de comportamiento por categorías, una habilidad clave del módulo `5.1 GroupBy.ipynb`.
* **Profundización en Métodos de Pandas:** Claridad en el uso de funciones como `len()` vs. `count()`, y la comprensión de cómo la inmutabilidad de tipos afecta operaciones como `.copy()`.

### 🧪 El Desafío de la Prueba de Hipótesis (Fase 3)

La fase final del ejercicio representó un reto importante, centrado en la prueba de hipótesis para evaluar si existen diferencias significativas en el número de vuelos reservados por **nivel educativo**.

* **Objetivo:** Determinar la existencia de diferencias estadísticamente relevantes entre los grupos de clientes según su educación en cuanto a sus vuelos reservados.
* **Proceso de Aprendizaje:** En esta sección, se ha trabajado con la función `prueba_hipotesis` proporcionada en el material del curso (`9. Estadística_Inferencial.ipynb`). Aunque la función está diseñada para comparar dos grupos, el ejercicio implicó adaptar su lógica para explorar la comparación entre **múltiples niveles educativos**. Para ello, se aplicaron los pasos de:
    * Verificación de la normalidad de los datos de cada grupo (utilizando `scipy.stats.shapiro` o `scipy.stats.kstest` según el tamaño de la muestra, comparando con una distribución normal estándar, tal como se ve en el notebook `9. Estadística_Inferencial.ipynb`).
    * Evaluación de la homogeneidad de varianzas (con `scipy.stats.bartlett` o `scipy.stats.levene`).
    * Finalmente, la función adapta su lógica para elegir la prueba estadística apropiada para **múltiples grupos** (ANOVA o Kruskal-Wallis H), basándose en los conceptos de los apuntes y permitiendo una aproximación más completa al problema planteado.

Este ejercicio, especialmente en su fase final, ha sido una valiosa oportunidad para practicar la estadística inferencial y aplicar estas herramientas con Python en un contexto real de análisis de datos.

## 👩‍💻 Autora

Inés García Oubiña (Ina G. Oubiña)

---
