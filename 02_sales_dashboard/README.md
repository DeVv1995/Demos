# 📊 Dashboard de Ventas Interactivo

Este proyecto permite crear un dashboard interactivo de análisis de ventas a partir de un archivo CSV. Utilizando **Pandas** y **Plotly**, se generan visualizaciones que permiten al usuario explorar métricas clave del negocio, como ventas totales, ticket promedio, productos más vendidos y distribución por ubicación y método de pago.

---

## 📌 Características

- Permite subir un archivo CSV con transacciones comerciales.
- Calcula automáticamente:
  - Total vendido
  - Cantidad de ítems vendidos
  - Ticket promedio
  - Número de transacciones únicas
- Visualiza datos con gráficos interactivos usando Plotly:
  - Ventas por fecha
  - Productos más vendidos
  - Ventas por ubicación
  - Métodos de pago más utilizados

---

## 🚀 Ejecución rápida (Google Colab)

Puedes ejecutar el proyecto directamente en Google Colab:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/)

---

## 📁 Dataset

👉 [DATOS CAFÉ LIMPIOS](https://www.kaggle.com/datasets/maurosteban99/datos-caf-limpios/data)

Debes subir un archivo CSV que contenga al menos las siguientes columnas:

| Columna            | Descripción                                |
|--------------------|--------------------------------------------|
| `Transaction ID`   | Identificador único de la transacción      |
| `Item`             | Nombre del producto vendido                |
| `Quantity`         | Cantidad vendida                           |
| `Price Per Unit`   | Precio por unidad                          |
| `Total Spent`      | Total gastado en la compra                 |
| `Payment Method`   | Método de pago utilizado                   |
| `Location`         | Ubicación donde se realizó la compra       |
| `Transaction Date` | Fecha de la transacción (formato fecha)    |

---


## 📊 Ejemplo de Resultados

| Funcionalidad                     | Descripción                                                                 |
|----------------------------------|-----------------------------------------------------------------------------|
| 🧾 **Métricas resumen automáticas** | Totales agregados de ventas, ítems y ticket promedio                       |
| 📅 **Visualización temporal de ventas** | Línea de evolución de ingresos por día                                    |
| 🛍️ **Ranking de productos y ubicaciones** | Barras y tortas interactivas con Plotly                                   |
| 💳 **Análisis por método de pago** | Gráficos de barras con frecuencia de los métodos de pago utilizados        |


---

## 🧩 Tecnologías utilizadas

| Herramienta         | Uso principal                           |
|---------------------|------------------------------------------|
| 🐍 **Python 3**        | Lenguaje principal del análisis          |
| 📊 **Pandas**           | Manipulación y análisis de datos         |
| 📈 **Plotly Express**   | Visualizaciones interactivas            |
| ☁️ **Google Colab**     | Entorno de ejecución recomendado         |


---

## 👨‍💻 Autor

**Danny Venegas**  
Ingeniero en Computación | Desarrollador Full Stack | UX/UI Enthusiast

🌐 [Portafolio web](#)  
📧 venegas.danny570@gmail.com  
💼 [LinkedIn](https://www.linkedin.com/in/danny-venegas-275726231)

---

⭐ ¡Gracias por visitar este proyecto! No olvides explorar el resto del portafolio.
