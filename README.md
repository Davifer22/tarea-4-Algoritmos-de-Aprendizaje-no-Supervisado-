Análisis y Agrupamiento de Datos No Supervisado
Descripción del Proyecto
Este proyecto tiene como objetivo aplicar técnicas de clustering no supervisado para analizar un conjunto de datos y descubrir agrupaciones naturales en las observaciones. Se utilizaron dos métodos principales de agrupamiento:

•	K-means
•	Clustering Jerárquico

Además, se implementó PCA (Análisis de Componentes Principales) para reducir la dimensionalidad y facilitar la visualización.
Pasos del Análisis

 1. Análisis Exploratorio de Datos (EDA)
    
•	Identificación de relaciones entre variables.
•	Detección de valores atípicos.
•	Observación de tendencias y distribución de los datos.
 2. Preprocesamiento de Datos
 
•	Limpieza de datos.
•	Tratamiento de valores faltantes.
•	Normalización y transformación según fue necesario.

 3. Selección de Características
    
•	Aplicación de técnicas para reducir dimensionalidad.
•	Selección de las variables más relevantes.

4. Entrenamiento del Modelo

•	Configuración de hiperparámetros.
•	Entrenamiento con K-means y Clustering Jerárquico.

5. Evaluación del Desempeño
Se utilizaron métricas como:

•	Coeficiente de Silhouette
•	Índice de Calinski-Harabasz

 6. Visualización de Resultados
    
•	Dendrograma del Clustering Jerárquico.
•	Gráficas de dispersión con PCA para visualizar los clusters.
•	Comparación visual de los grupos obtenidos por cada modelo.

 Conclusiones
•	Ambos métodos lograron identificar tres grupos claramente diferenciados.
•	K-means mostró una separación más compacta entre los clusters.
•	Clustering Jerárquico permitió observar la estructura jerárquica entre las observaciones, lo cual fue útil para comprender mejor el dataset.
•	La implementación de PCA fue clave para representar los datos en 2D y facilitar la interpretación visual de los resultados.


