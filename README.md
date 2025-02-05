# Análisis del Comportamiento del Usuario

## Contexto
Este proyecto se enfoca en el análisis del comportamiento del usuario dentro de una aplicación de una empresa emergente que vende productos alimenticios. El objetivo principal es estudiar el embudo de ventas y evaluar los resultados de un experimento A/A/B para determinar si un cambio en las fuentes de la aplicación afecta la interacción de los usuarios.

## Datos
El dataset utilizado contiene eventos generados por los usuarios, con las siguientes variables principales:
- **EventName:** Nombre del evento.
- **DeviceIDHash:** Identificador único del usuario.
- **EventTimestamp:** Marca de tiempo del evento.
- **ExpId:** Número de experimento (246 y 247 son los grupos de control, 248 es el grupo de prueba).

## Objetivos del Proyecto
1. **Análisis del embudo de ventas**: Evaluar en qué etapa del proceso los usuarios abandonan la aplicación y qué porcentaje completa una compra.
2. **Evaluación del experimento A/A/B**: Analizar si el cambio de fuente en la aplicación tiene un impacto significativo en la interacción de los usuarios.
3. **Validación de los grupos de control**: Comparar los grupos A/A para asegurarse de que la asignación de usuarios es correcta y no sesga los resultados.

## Herramientas Utilizadas
- **Python**: Lenguaje de programación principal para el análisis de datos.
- **Pandas**: Manipulación y limpieza de datos.
- **Matplotlib**: Visualización de datos.
- **SciPy**: Pruebas estadísticas para evaluar diferencias entre grupos.
- **Jupyter Notebook**: Desarrollo y presentación del análisis.

## Resultados y Conclusiones
- Se identificaron las tasas de conversión en cada etapa del embudo de ventas.
- Se encontró la etapa con mayor pérdida de usuarios y se hicieron recomendaciones para mejorar la retención.
- Se evaluó el impacto del cambio de fuentes en el grupo de prueba y se comparó con los grupos de control para determinar su efecto en la interacción del usuario.
