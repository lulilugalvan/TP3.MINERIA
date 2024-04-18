# TP3.MINERIA
import pandas as pd #Esta línea importa la librería pandas y la renombra como 'pd' para que sea más fácil de usar en el código. Pandas es una biblioteca de Python que proporciona estructuras de datos y herramientas de análisis de datos.
import numpy as np #Similar al paso anterior, esta línea importa la librería numpy y la renombra como 'np'. NumPy es otra biblioteca de Python utilizada para realizar operaciones numéricas y matriciales eficientes.

from google.colab import drive #Esta línea importa el módulo 'drive' desde la biblioteca 'google.colab'. Google Colab es un entorno de desarrollo en línea basado en Jupyter Notebook que permite ejecutar código de Python en la nube. El módulo 'drive' proporciona funcionalidades para montar Google Drive en el entorno de Colab.
drive.mount('/content/drive') # Esta línea llama a la función 'mount' del módulo 'drive' para montar Google Drive en el entorno de Colab. Montar Google Drive permite acceder a los archivos almacenados en Google Drive desde el entorno de Colab.

nfl_data = pd.read_csv("/content/drive/MyDrive/IMD/dataMining2024/TP3/Fantantes(2).csv") #Esta línea utiliza la función 'read_csv' de pandas para leer un archivo CSV y cargar sus datos en un DataFrame de pandas. Un DataFrame es una estructura de datos tabular similar a una tabla de base de datos. El archivo CSV se encuentra en la ruta especificada, que está dentro de Google Drive debido al montaje anterior.

np.random.seed(0) #Esta línea establece una semilla aleatoria para el generador de números aleatorios de la biblioteca numpy. Establecer una semilla aleatoria garantiza que los números aleatorios generados sean reproducibles, es decir, si ejecutas el mismo código varias veces, obtendrás los mismos resultados aleatorios. La semilla '0' se utiliza comúnmente para fines de demostración y reproducibilidad.
