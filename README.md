# -Analisis-de-Comportamiento-del-Cliente-ConnectaTel-2024
Análisis de datos en Python para ConnectaTel utilizando Pandas y Seaborn. El proyecto integra tres fuentes de datos para identificar patrones de consumo, limpiar inconsistencias (valores sentinel y fechas), detectar outliers y segmentar clientes por edad  y comportamiento, transformando métricas en insights para optimizar la oferta comercial.

*🎯 Objetivo del Proyecto*

Este proyecto tiene como fin analizar el comportamiento de los clientes de ConnectaTel (empresa de telecomunicaciones en México y Colombia). El análisis busca transformar datos crudos de uso de servicios móviles (llamadas y mensajes) en insights estratégicos para:

* Identificar patrones de consumo por edad y plan.

* Detectar comportamientos atípicos (outliers) que sugieran fraude o necesidades especiales.

* Segmentar a los usuarios para optimizar la oferta comercial y mejorar la retención (churn).

📂 Datasets Utilizados
El análisis integra tres fuentes de datos principales:

plans.csv: Detalle de los planes (Precios, minutos/GB incluidos y costos adicionales).

users_latam.csv: Información demográfica de los clientes (Edad, ciudad, fecha de registro, plan contratado).

usage.csv: Actividad real de los usuarios (Duración de llamadas y longitud de mensajes).

🛠️ Etapas del Análisis
El proyecto sigue un flujo de trabajo de Ciencia de Datos estructurado:

Exploración de Datos (EDA): Identificación de estructuras y tipos de variables.

Control de Calidad y Limpieza: Tratamiento de valores sentinel (como el -999 en edad), manejo de nulos lógicos, corrección de fechas fuera de rango y estandarización.

Análisis Estadístico: Cálculo de medidas de tendencia central y dispersión para entender el comportamiento típico y extremo.

Visualización de Outliers: Uso de Boxplots e Histogramas para detectar patrones inusuales.

Segmentación: Creación de perfiles de clientes basados en el nivel de uso y demografía.

Insights Ejecutivos: Traducción de hallazgos técnicos en recomendaciones de negocio.

🚀 Cómo ejecutar el Proyecto
Puedes visualizar y ejecutar este análisis de dos formas:

Opción 1: Google Colab (Recomendado)
Haz clic en el siguiente botón (si tienes configurado el enlace): 

Sube los archivos .csv a la carpeta de archivos de la sesión en Colab.

Ejecuta todas las celdas (Ctrl + F9).

Opción 2: Localmente (Jupyter Notebook)
Clona este repositorio:

Bash
git clone https://github.com/[TU_USUARIO]/[NOMBRE_REPOSITORIO].git
Instala las dependencias necesarias:

Bash
pip install pandas numpy matplotlib seaborn
Abre Jupyter Notebook o VS Code y ejecuta S7 Version-Estudiante-Project-ConnectaTel.ipynb.

📋 Guía de Reproducción
Para replicar los resultados obtenidos en el reporte:

Carga de Datos: Asegúrate de que los archivos plans.csv, users_latam.csv y usage.csv estén en la misma ruta que el notebook.

Preprocesamiento: Ejecuta las celdas de limpieza para tratar los valores -999 y las fechas del año 2026.

Análisis: Las funciones de visualización generarán automáticamente los gráficos de distribución que sustentan el análisis de segmentos.

Resultados: Dirígete a la sección final del notebook para leer las conclusiones sobre las oportunidades comerciales detectadas.
