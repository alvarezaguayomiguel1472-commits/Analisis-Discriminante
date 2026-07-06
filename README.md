# Analisis-Discriminante
Objetivo: Implementación de algoritmos de Análisis Discriminante Lineal y Análisis Discriminante Cuadrático en el conjunto de dataset "Wine.csv"

## Origen de los datos
Los datos analizados en este proyecto provienen de una fuente externa compartida públicamente.

* **Fuente de los datos:** (https://drive.google.com/file/d/1GeH8W1zFuq9XH2qaS66JJEXJh2QuO292/view)
* **Formato original:** CSV
* **Fecha de acceso:** Julio 2026

## Flujo de Trabajo 
El flujo de trabajo del proyecto contó con las siguientes etapas: 
* **Configuración y Carga de Datos:** importación de las librerias necesarias y del dataset
* **Descripción del conjunto de datos:** uso de funciones de pandas y de numpy para obtener datos sobre la estructura del conjunto de datos como nombres de variables, nombres de clases y número de clases.
* **Exploración de datos:** descripcion de tamaño del dataset, distribución de clases, información sobre tipos de variables y valores nulos.
* **Visualización de los datos:** gráficos de correlacion de variables (heatmap), dispersión de clases (scatterplot), histograma de clases por variable e histograma de distribución de clases. 
* **Preparación de los datos:** división de datos de entrenamiento y de prueba, estandarización de variables numéricas.
* **Implementación de LDA:** Entrenamiento del modelo LDA y cálculo de métricas.
* **Implementación de QDA:** Entrenamiento del modelo QDA y cálculo de métricas.
* **Comparación de modelos:** Comparación de métricas de evaluación de rendimiento de ambos modelos.
* **Fronteras de decisión:** Entrenamiento de los modelos con dos variables y grafica de los fronteras.

## Librerías 
Para llevar a cabo este proyecto se utilizaron las siguientes librerías: 
* **Python:** Lenguaje de programación adecuado para proyectos de ciencias de datos.
* **Pandas:** manipulación de datos.
* **Numpy:** cálculos matemáticos.
* **Matplotlib: ** Elaboración de gráficos.
* **Seaborn:** Librería que en combinación con Matplotlib permite realizar gráficos estadísticos.
* **ScikitLearn:** Librería utilizada para machine learning.

## Conclusiones
| Métrica | LDA (Linear) | QDA (Quadratic) |
| :--- | :---: | :---: |
| **Accuracy** | *0.944* | *0.962* |
| **Precision** | *0.946* | *0.966* |
| **Recall** | *0.944* | *0.962* |
| **F1-Score** | *0.945* | *0.962* |
| **Tiempo (seg)** | *0.019* | *0.002* |

QDA es superior a LDA para este conjunto de datos.

