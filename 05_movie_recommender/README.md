# 🎬 Sistema Recomendador de Películas por Género

Este proyecto implementa un sistema recomendador de películas utilizando técnicas de procesamiento de lenguaje natural (NLP). En este caso, las recomendaciones se basan en la similitud de género y clasificación de MPAA (Rating). Usamos **TF-IDF** y **Similitud del Coseno** para encontrar las películas más similares.

---

## 📌 Características

- Recomendaciones basadas en el género y la clasificación de MPAA.
- Utiliza **TF-IDF** para vectorizar las características del contenido.
- Calcula la similitud entre películas usando la métrica de **cosine similarity**.
- Permite al usuario ingresar el título de una película y obtener recomendaciones similares.

---

## 🚀 Ejecución rápida (Google Colab)

Puedes ejecutar el proyecto directamente en Google Colab:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/16fgl5fW9qDLX-dh0h7lxgPLbmNtLuY-W?usp=sharing)

---

## 📁 Dataset

Este proyecto usa un dataset con las siguientes columnas:

| Columna                | Descripción                                    |
|------------------------|------------------------------------------------|
| `movie_title`          | Título de la película                          |
| `release_date`         | Fecha de estreno de la película                |
| `genre`                | Género de la película                          |
| `mpaa_rating`          | Clasificación de la película (MPAA Rating)     |
| `total_gross`          | Ingresos totales de la película                |
| `inflation_adjusted_gross` | Ingresos ajustados por inflación             |

Asegúrate de que tu archivo CSV esté estructurado de esta forma.
Puedes descargar un ejemplo desde Kaggle:  
👉 [Disney Movies](https://www.kaggle.com/datasets/prateekmaj21/disney-movies/data)

---

## 📊 Métricas y Visualizaciones

| Sección                     | Descripción                                                |
|-----------------------------|------------------------------------------------------------|
| 📚 Recomendaciones          | Recomendaciones basadas en el título de la película        |
| 🎯 Similaridad de Género    | Comparación entre películas con géneros y ratings similares|
| 🎥 Películas Similares      | Top 5 películas recomendadas                              |

---

## 🧩 Tecnologías utilizadas

| Herramienta               | Uso principal                                  |
|---------------------------|------------------------------------------------|
| 🐍 **Python 3**           | Lenguaje principal del análisis                |
| 📊 **Pandas**             | Manipulación y análisis de datos               |
| 🧠 **Scikit-learn**       | Modelos de machine learning (cosine similarity) |
| 📖 **TF-IDF**             | Vectorización del texto                         |
| 💻 **Google Colab**       | Entorno de ejecución recomendado               |

---

## 👨‍💻 Autor

**Danny Venegas**  
Ingeniero en Computación | Desarrollador Full Stack | UX/UI Enthusiast

🌐 [Portafolio Web](#)  
📧 venegas.danny570@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/danny-venegas-275726231)

---

⭐ Gracias por visitar este repositorio. Explora los proyectos y si te resultan útiles o interesantes, ¡no dudes en dejar una estrella!
