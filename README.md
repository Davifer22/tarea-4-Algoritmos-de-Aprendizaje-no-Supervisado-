# Análisis de Clustering No Supervisado con K-means y Clustering Jerárquico

## Descripción del Proyecto

Este proyecto tiene como objetivo aplicar técnicas de aprendizaje no supervisado para analizar un conjunto de datos y encontrar patrones ocultos mediante agrupamiento (clustering). Se implementaron los algoritmos K-means y Clustering Jerárquico utilizando Python y bibliotecas como `scikit-learn`, `matplotlib`, `seaborn` y `scipy`. Se aplicaron pasos de análisis exploratorio, limpieza de datos, selección de características, entrenamiento y evaluación de modelos.

---

## Contenido del Jupyter Notebook

El notebook incluye:

1. **Carga del Dataset**  
   - Lectura de datos desde archivo CSV  
   - Visualización inicial de columnas y estructura  

2. **Análisis Exploratorio de Datos (EDA)**  
   - Gráficos de caja (boxplots) para detectar valores atípicos  
   - Matriz de correlación para analizar relaciones entre variables  

3. **Preprocesamiento**  
   - Limpieza de datos  
   - Normalización y transformación para escalar los datos  

4. **Selección de Características**  
   - Reducción de dimensionalidad con PCA (Análisis de Componentes Principales)  

5. **Modelado**  
   - **K-means Clustering** con configuración de hiperparámetros y uso del método del codo  
   - **Clustering Jerárquico** con generación de dendrograma  

6. **Evaluación del Modelo**  
   - Métricas utilizadas:  
     - Coeficiente de Silhouette  
     - Índice de Calinski-Harabasz  

7. **Visualización de Resultados**  
   - Dendrograma  
   - Gráficos de dispersión con reducción PCA para visualizar agrupaciones  
   - Comparación de agrupaciones de ambos modelos

---

## Interpretación de Resultados

La interpretación y el análisis detallado de los resultados se encuentran documentados en el archivo Word adjunto al proyecto, donde se explican los gráficos generados, se analizan los patrones encontrados y se exponen las conclusiones comparativas entre los modelos.

---

## Requisitos

- Python 3.x  
- Jupyter Notebook  
- Bibliotecas:
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  
  - scipy  

---

## Cómo Ejecutar el Proyecto

1. Clona el repositorio o descarga el notebook `.ipynb`
2. Asegúrate de tener instaladas las bibliotecas necesarias (`pip install -r requirements.txt` si está disponible)
3. Abre el archivo en Jupyter Notebook
4. Ejecuta cada celda en orden para visualizar resultados y gráficos

---

## Autor

David Fernando Manrique Montaño 


