# proyecto_udacity_Datascience

📊 Proyecto Final de Data Science - Udacity
📌 Motivación del Proyecto
La educación es uno de los factores clave para el desarrollo social y económico de los países. Este proyecto analiza indicadores educativos globales con datos del Banco Mundial para responder preguntas como:

¿Cómo ha cambiado el acceso a la educación a lo largo del tiempo en diferentes regiones?
¿Qué países muestran avances o retrocesos importantes?
¿Qué relación existe entre ciertos indicadores educativos?

🧾 Archivos del Repositorio
datascience_udacity.ipynb: Notebook principal con el análisis exploratorio, visualizaciones, preparación de datos y modelos predictivos.

data/: Carpeta que contiene los archivos originales descargados desde el Banco Mundial (por ejemplo, Education World Bank.csv).
README.md: Este archivo, con la descripción del proyecto.
images/: Visualizaciones usadas tanto en el notebook como en la entrada de blog.

⚙️ Instalación
Este proyecto se ejecuta en Python 3.10 y utiliza bibliotecas comunes de análisis de datos. 


📈 Resumen de Resultados
Se limpió y transformó el dataset educativo de forma que los años fueran columnas numéricas.
Se analizaron patrones de acceso a la educación entre países y regiones.
Se entrenó un modelo de regresión (Random Forest) para predecir valores futuros de indicadores educativos.
El desempeño del modelo fue evaluado con métricas como MAE y R².

🔬 Qué funcionó y qué no
✅ La exploración visual permitió identificar tendencias claras.
✅ La transformación de los datos por años fue clave para construir los modelos.
❌ Algunos datos faltantes limitaron la capacidad predictiva en ciertas series temporales.
🔁 Se probaron diferentes algoritmos antes de elegir Random Forest como el más estable.

👩‍💻 Cómo interactuar con el proyecto
Este proyecto no requiere ejecución en tiempo real. Se puede revisar paso a paso en el notebook. Si deseas replicar los resultados, simplemente descarga el repositorio, instala las dependencias y ejecuta el archivo .ipynb.

🧑‍🤝‍🧑 Autores y Agradecimientos
Este proyecto fue desarrollado por Viviana Reina Díaz como parte del programa de Data Science de Udacity.
Agradezco al equipo de tutores de Udacity, a quienes comparten recursos sobre limpieza de datos educativos, y al Banco Mundial por su repositorio de datos abiertos.
