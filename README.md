# Trabajo de Consulta: EDA, Limpieza de Datos y Herramientas de IA

## Objetivo
Investigar y comprender los conceptos fundamentales del Análisis Exploratorio de Datos (EDA), con un enfoque especial en las fases de limpieza de datos y la integración de herramientas de Inteligencia Artificial para optimizar este proceso.

## Indicaciones
Responde a los siguientes puntos de manera clara y fundamentada. Utiliza ejemplos prácticos y referencias para apoyar tus respuestas.

## Aspectos a Investigar y Desarrollar

1. **Definición del Análisis Exploratorio de Datos (EDA):**
   - Define qué es el EDA y su importancia en el análisis de datos.  
     _Incluye ejemplos breves que resalten su propósito._

2. **Objetivos del EDA:**
   - Describe los principales objetivos que se persiguen al realizar un EDA.

3. **Fases del EDA: Enfoque en Limpieza de Datos:**
   - Describe brevemente el flujo general del EDA, pero **centra tu investigación y documentación detallada** en la etapa de **Limpieza de Datos**.
   - Utiliza herramientas de IA (como Gemini o Julius) para investigar y explicar cómo se ejecutan los siguientes procesos, documentando cada uno:
     1. **Detectar y manejar valores faltantes:** Estrategias de imputación o eliminación.
     2. **Eliminar duplicados:** Importancia de la unicidad de los registros.
     3. **Corregir tipos de datos:** Asegurar que números sean números, fechas sean fechas, etc.
     4. **Normalizar y limpiar texto:** Unificación de formatos, mayúsculas/minúsculas, eliminación de espacios extra.
     5. **Manejo de valores atípicos (outliers):** Identificación y decisión sobre su tratamiento.
     6. **Renombrar columnas:** Estandarización de nombres para facilitar el análisis.

4. **Herramientas del EDA (Estadística Descriptiva y Visualización):**
   - Explica el papel de la Estadística Descriptiva en el EDA. Incluye las medidas de:
     - **Tendencia central:** media, mediana, moda.  
     - **Dispersión:** desviación estándar, varianza, rango intercuartílico.
   - Describe el uso de visualizaciones gráficas (ej.: histogramas, diagramas de caja, gráficos de dispersión...).

5. **Caso Práctico con IA (Ejecución por Fases):**
   - **Herramientas IA:** Investiga y utiliza herramientas como **Julius AI**, **Gemini**, para realizar este ejercicio.
   - **Dataset:** Utiliza el siguiente archivo de datos de **películas (Movies)** para tu análisis:
     - [Enlace al Dataset (Google Drive)](https://drive.google.com/file/d/1uHvGXxrcULwZM0QiKZeCpu94GGlcHhiG/view?usp=drive_link)
     - *Columnas disponibles:* `adult`, `belongs_to_collection`, `budget`, `genres`, `homepage`, `id`, `imdb_id`, `original_language`, `original_title`, `overview`, `popularity`, `poster_path`, `production_companies`, `production_countries`, `release_date`, `revenue`, `runtime`, `spoken_languages`, `status`, `tagline`, `title`, `video`, `vote_average`, `vote_count`, `keywords`, `cast`, `crew`, `ratings`.
   
   - **Actividad - Realiza el EDA en las siguientes 3 Fases:**

     **Fase 1: Resumen y Limpieza (Vista General) - *Punto Principal***
     - Carga los datos en la IA y solicita un resumen general (`info`, `head`).
     - **Ejecuta y documenta** obligatoriamente los 6 pasos de limpieza definidos en la sección 3:
       1. Detección de nulos.
       2. Eliminación de duplicados.
       3. Corrección de tipos de datos (ej. fechas o números guardados como texto).
       4. Limpieza de texto.
       5. Detección de Outliers.
       6. Renombrado de columnas (si es necesario).
     - *Entregable:* Capturas o descripción de cómo la IA resolvió cada uno de estos problemas de calidad de datos.

     **Fase 2: Análisis Univariable (Caso de Estudio)**
     - Elige variables de interés (ej. `budget`, `revenue`, `vote_average`, `runtime`).
     - **Caso de Estudio:** Realiza un análisis profundo de **una** variable o un grupo pequeño de variables individuales.
       - Pide a la IA estadísticas descriptivas y gráficos de distribución (histogramas/boxplots) para esa variable.
     - *Entregable:* Interpretación de la distribución de la variable elegida.

     **Fase 3: Análisis Bivariable / Multivariable (Relaciones)**
     - Solicita a la IA que explore relaciones entre variables (ej. *Budget vs Revenue*, *Vote Average vs Popularity*).
     - *Entregable:* Un gráfico de dispersión o matriz de correlación generado por la IA con su interpretación.

6. **Referencias:**
   - Agregar fuentes confiables que respalden la información proporcionada. _(Formato APA 7 Edición)._

---

## Formato de Entrega 
- **Formato:** Documento tipo Wiki sobre este archivo README.md
- **Fecha de Entrega:** 18 de diciembre 2025.  
- **Evaluación:** Se priorizará la calidad y detalle en la **Fase 1 (Limpieza)**, la correcta ejecución del caso de estudio univariable y la evidencia del uso de IA.

---

## Nota
Este trabajo será discutido en clase. Prepárate para mostrar cómo las herramientas de IA te ayudaron a limpiar y entender los datos del caso práctico de películas.
