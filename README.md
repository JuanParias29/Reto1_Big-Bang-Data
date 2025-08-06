# Reto1_Big-Bang-Data

Este proyecto presenta un ejercicio práctico de análisis de datos aplicados a los resultados de una prueba de cultura general, enfocado en la **limpieza, validación y exploración de datos**, así como en el cálculo de métricas de eficiencia.

## 🎯 Objetivo

Desarrollar un proceso de análisis de calidad de datos que permita:
- Identificar y eliminar registros inválidos o inconsistentes.
- Medir el rendimiento de los participantes mediante distintas métricas.
- Construir una métrica compuesta de eficiencia (`RESPUESTAS_POR_SEGUNDO`).
- Establecer criterios objetivos para determinar el mejor desempeño.
- Explorar las posibilidades futuras de entrenamiento de modelos predictivos.

---

## 🧰 Tecnologías utilizadas

- Python 3
- Pandas
- Google Colab
- Jupyter Notebook
- Markdown

---

## 🧹 Principales tareas realizadas

- Eliminación de tiempos negativos, nulos o excesivamente altos.
- Eliminación de nombres vacíos y registros duplicados (manteniendo el mejor intento).
- Cálculo de métricas como:
  - Número de respuestas correctas.
  - Tiempo total en responder.
  - Respuestas por segundo (eficiencia).
- Análisis de:
  - Top 3 en menor tiempo.
  - Top 3 en mayor número de respuestas correctas.
  - Top 3 en mejor tasa de respuestas por segundo.

---

## 🧪 Resultados

A partir del análisis, se determinaron los estudiantes con mejor desempeño considerando la métrica `RESPUESTAS_POR_SEGUNDO`, que combina velocidad y precisión. También se mostraron rankings separados por tiempo y por respuestas correctas.

---

## 🚀 Ejecución del proyecto

1. Abre el archivo `.ipynb` en Google Colab.
2. Sube tu archivo de resultados en formato `.xlsx` o `.csv`.
3. Ejecuta cada celda para realizar el proceso de limpieza, análisis y visualización.
4. Explora los resultados generados y modifica el código si deseas aplicar nuevas métricas.

---

## 🔮 Trabajo futuro

Este ejercicio demuestra cómo aplicar principios básicos de **calidad de datos**. A futuro, se puede extender el análisis hacia:
- Predicción de puntajes usando modelos de machine learning.
- Agrupamiento de estudiantes según patrones de respuesta.
- Análisis de características adicionales (edad, formación, etc.) para mejorar la interpretación.

---

## 📁 Repositorio

---

## ✍️ Autor

**Juan Pablo Arias**  
Estudiante de Ciencia de Datos
Pontificia Universidad Javeriana  
