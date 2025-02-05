# Análisis del Comportamiento del Usuario / User Behavior Analysis

## Contexto / Context
Este proyecto se enfoca en el análisis del comportamiento del usuario dentro de una aplicación de una empresa emergente que vende productos alimenticios. El objetivo principal es estudiar el embudo de ventas y evaluar los resultados de un experimento A/A/B para determinar si un cambio en las fuentes de la aplicación afecta la interacción de los usuarios.

This project focuses on analyzing user behavior within an app from a startup that sells food products. The main goal is to study the sales funnel and evaluate the results of an A/A/B experiment to determine whether a change in the app’s fonts affects user interaction.

## Datos / Data
El dataset utilizado contiene eventos generados por los usuarios, con las siguientes variables principales:
- **EventName:** Nombre del evento.
- **DeviceIDHash:** Identificador único del usuario.
- **EventTimestamp:** Marca de tiempo del evento.
- **ExpId:** Número de experimento (246 y 247 son los grupos de control, 248 es el grupo de prueba).

---

The dataset used contains user-generated events with the following key variables:
- **EventName:** Name of the event.
- **DeviceIDHash:** Unique user identifier.
- **EventTimestamp:** Event timestamp.
- **ExpId:** Experiment number (246 and 247 are control groups, 248 is the test group).

## Objetivos del Proyecto / Project Objectives
1. **Análisis del embudo de ventas**: Evaluar en qué etapa del proceso los usuarios abandonan la aplicación y qué porcentaje completa una compra.
2. **Evaluación del experimento A/A/B**: Analizar si el cambio de fuente en la aplicación tiene un impacto significativo en la interacción de los usuarios.
3. **Validación de los grupos de control**: Comparar los grupos A/A para asegurarse de que la asignación de usuarios es correcta y no sesga los resultados.

---

1. **Sales funnel analysis:** Evaluate at which stage users drop off and what percentage completes a purchase.
2. **A/A/B experiment evaluation:** Analyze whether the font change in the app has a significant impact on user interaction.
3. **Validation of control groups:** Compare the A/A groups to ensure proper user assignment and prevent biased results.

## Herramientas Utilizadas / Tools Used
- **Python**: Lenguaje de programación principal para el análisis de datos.
- **Pandas**: Manipulación y limpieza de datos.
- **Matplotlib**: Visualización de datos.
- **SciPy**: Pruebas estadísticas para evaluar diferencias entre grupos.
- **Jupyter Notebook**: Desarrollo y presentación del análisis.

---

- **Python:** Primary programming language for data analysis.
- **Pandas:** Data manipulation and cleaning.
- **Matplotlib:** Data visualization.
- **SciPy:** Statistical tests to evaluate differences between groups.
- **Jupyter Notebook:** Development and presentation of the analysis.

## Resultados y Conclusiones / Results and Conclusions
- Se identificaron las tasas de conversión en cada etapa del embudo de ventas.
- Se encontró la etapa con mayor pérdida de usuarios y se hicieron recomendaciones para mejorar la retención.
- Se evaluó el impacto del cambio de fuentes en el grupo de prueba y se comparó con los grupos de control para determinar su efecto en la interacción del usuario.

---

- Conversion rates were identified at each stage of the sales funnel.
- The stage with the highest user drop-off was found, and recommendations were made to improve retention.
- The impact of the font change on the test group was evaluated and compared to the control groups to determine its effect on user interaction.
