# 📊 Actividad: TF-IDF | Emotion Dataset

### Autor: Jhostyn G.

El código de este proyecto muestra un ejemplo completo de cómo procesar, analizar y clasificar un conjunto de datos de emociones utilizando TF-IDF y un modelo de aprendizaje automático.

## 📁 Estructura del Proyecto

```
└── 📁TF-IDF
    └── 📁.ipynb_checkpoints
        └── GavilanezJhostyn_tf-idf-emotion-dataset-checkpoint.ipynb
    └── 📁archive
        └── Emotion_classify_Data.csv
    └── GavilanezJhostyn_tf-idf-emotion-dataset.ipynb
    └── README.md
    └── 📁results
        ├── corpora
    └── 📁__results___files
        └── wordcloud_result_1.png
        └── wordcloud_result_2.png
        └── wordcloud_result_3.png
        └── wordcloud_result_4.png
```

##  📦 Librerías Utilizadas
Las siguientes librerías de Python se utilizan en este proyecto:

* Pandas - Manejo de datos
* Numpy - Operaciones numéricas
* Matplotlib - Visualizaciones básicas
* Seaborn - Visualizaciones avanzadas
* NLTK - Procesamiento del lenguaje natural (PLN)
* Wordcloud - Generación de nubes de palabras


## 📊 Descripción del Proyecto
Este proyecto tiene como objetivo analizar un conjunto de datos de emociones utilizando la técnica de TF-IDF (Term Frequency-Inverse Document Frequency) para transformar el texto en características que puedan ser utilizadas por un modelo de aprendizaje automático para clasificar las emociones.

## 📝 Pasos Principales

**1.- Preprocesamiento de Datos:**

* Carga del conjunto de datos
* Limpieza de texto (eliminación de stopwords, tokenización, lematización)

**2.- Análisis Exploratorio de Datos (EDA):**
* Visualización de la distribución de las emociones
* Generación de nubes de palabras (word clouds) para las diferentes emociones

**3.- Vectorización TF-IDF:**
* Conversión del texto preprocesado en vectores TF-IDF

**4.- Entrenamiento y Evaluación del Modelo:**
* Entrenamiento de un modelo de clasificación utilizando los vectores TF-IDF
* Evaluación del modelo mediante métricas de precisión, recall y F1-score

## 📈 Resultados
Se generan varias visualizaciones que muestran el análisis exploratorio y los resultados del modelo, incluyendo:

* Distribución de las emociones en el conjunto de datos
* Nubes de palabras que destacan las palabras más frecuentes por emoción
* Métricas de evaluación del modelo de clasificación

## 🚀 Cómo Empezar

* Clona este repositorio: ```git clone https://github.com/Jhostyn-2003/TF-IDF-Analisis-emociones.git```
* Navega al directorio del proyecto: ```cd TF-IDF```
* Instala las dependencias necesarias:``` pip install -r requirements.txt```
* Ejecuta el notebook para ver el análisis completo: ```jupyter notebook GavilanezJhostyn_tf-idf-emotion-dataset.ipynb```

## ✨ Contribuciones
¡Las contribuciones son bienvenidas! Siéntete libre de abrir un issue o enviar un pull request para mejorar el proyecto.

## ⌨️ con ❤️ por Jhostyn Gavilanez 
