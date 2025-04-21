# 🧠 Análisis de Sentimiento en Tweets

Este proyecto realiza un análisis de sentimiento sobre un conjunto de tweets utilizando técnicas de procesamiento de lenguaje natural (NLP). Se utiliza la librería **TextBlob** para clasificar los textos como **positivos**, **negativos** o **neutrales**, y se comparan los resultados con las etiquetas originales del dataset.

---

## 📌 Características

- Permite subir un archivo CSV con columnas: `textID`, `text`, `selected_text`, `sentiment`.
- Clasifica el sentimiento de cada tweet con `TextBlob`.
- Visualiza la distribución de sentimientos reales vs. predichos.
- Incluye matriz de confusión para evaluar precisión.
- Explicación automática de los resultados al final del análisis.

---

## 🚀 Ejecución rápida (Google Colab)

Puedes ejecutar el proyecto directamente en Google Colab:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

---

## 📁 Dataset

Utiliza el dataset de la competencia de Kaggle:  
👉 [Tweet Sentiment Extraction](https://www.kaggle.com/competitions/tweet-sentiment-extraction/data)

Asegúrate de que tu archivo CSV tenga al menos las siguientes columnas:

- `textID`: ID del tweet.
- `text`: Texto del tweet completo.
- `selected_text`: Frase que representa el sentimiento.
- `sentiment`: Sentimiento original (`positive`, `neutral`, `negative`).

---

## 🧩 Tecnologías utilizadas

Python 3

Pandas

TextBlob

Matplotlib / Seaborn

Scikit-learn (confusion matrix)

Google Colab (recomendado)

---

## 👨‍💻 Autor

Danny Venegas

Ingeniero en Computación | Desarrollador Full Stack | UX/UI Enthusiast

🌐 //

💼 www.linkedin.com/in/danny-venegas-275726231

📧 venegas.danny570@gmail.com

¡Gracias por visitar este proyecto! Si te pareció interesante, no dudes en dejar una ⭐ y explorar el resto del portafolio.
