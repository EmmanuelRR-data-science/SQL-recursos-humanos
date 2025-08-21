# Proyecto de Análisis de Recursos Humanos con SQL y Python

## 📝 Descripción del Proyecto
Este proyecto es un análisis completo de los datos de empleados de una empresa para investigar las causas de la rotación de personal. El objetivo principal fue identificar si factores como el rendimiento, el salario y la antigüedad tienen alguna correlación con la salida de los empleados.

Para lograrlo, se realizaron consultas **SQL avanzadas** para extraer y agregar datos, y **Python** con la librería **Pandas** para el manejo de fechas y la creación de visualizaciones claras y directas.

## 🛠️ Herramientas y Tecnologías
- **SQL (SQLite):** Motor de base de datos ligero utilizado para consultas, agregaciones (`GROUP BY`, `COUNT`, `AVG`) y análisis de tendencias.
- **Python (Pandas, Matplotlib, Seaborn):**
  - **Pandas** para la manipulación y preparación de datos.
  - **Matplotlib** y **Seaborn** para la creación de visualizaciones que faciliten la interpretación de los resultados.
- **Google Colab:** Entorno de notebook en la nube para ejecutar el código de manera interactiva.
- **GitHub:** Plataforma para el control de versiones y la presentación del proyecto.

## 📊 Hallazgos y Conclusiones Clave
El análisis de los datos reveló una tasa de rotación masiva y uniforme. A diferencia de lo que se podría esperar, los datos mostraron que la rotación **no está concentrada en un grupo demográfico, de rendimiento o salarial específico**. La tasa de rotación es consistentemente alta en todas las métricas analizadas, lo que apunta a problemas sistémicos y no a factores individuales.

- **Rotación por Rendimiento:** No se encontró una correlación. La tasa de rotación de los empleados con rendimiento sobresaliente (`Exceeds`) es prácticamente idéntica a la de aquellos con bajo rendimiento.
- **Rotación por Salario:** La rotación también es uniforme entre los diferentes rangos salariales, lo que sugiere que el nivel de compensación no es el factor principal que impulsa la salida de los empleados.
- **Rotación por Antigüedad:** Los datos muestran una rotación del 100% en todos los grupos de antigüedad (menos de 1 año, 1-3 años, etc.), lo que indica que el problema de retención existe desde el momento de la incorporación y se mantiene a lo largo de la trayectoria profesional del empleado.

## 💡 Recomendaciones para la Empresa
Basado en los hallazgos de este análisis, se proponen las siguientes acciones para mitigar la rotación de empleados:

1. **Realizar un Análisis Cualitativo:** Llevar a cabo encuestas de salida y entrevistas con ex-empleados para obtener un contexto cualitativo y comprender las verdaderas causas de la rotación (ej. falta de desarrollo profesional, problemas de liderazgo, o cultura laboral).
2. **Revisar Procesos de Incorporación (Onboarding):** Un alto índice de rotación en los primeros años puede ser un síntoma de un proceso de incorporación deficiente. Se debe asegurar que los nuevos empleados se sientan apoyados, conectados y productivos desde el principio.
3. **Evaluar la Cultura y el Liderazgo:** La uniformidad de la rotación en todas las métricas es una fuerte señal de que el problema reside en la cultura de la empresa o en la calidad de la gestión.

## 🤝 Contribuciones
Siéntete libre de clonar este repositorio y explorar el código. Las sugerencias y mejoras son bienvenidas.
