# Implementacion-JBVN-A01751694
GitHub para guardar trabajos de portafolio de Implementación por Josué Bernardo Villegas Nuño - A01751694 

**Requisitos: A01751694_EMAPP_Analisis y A01751694_PDM_Implemen**

**Dependencias:**
- [Node.js](https://nodejs.org/): Asegúrate de tener Node.js instalado en tu sistema.
- [npm](https://www.npmjs.com/): Gestor de paquetes de Node.js, necesario para instalar las dependencias del proyecto.

**Instalación:**
1. Clona este repositorio usando el comando `git clone`.
2. Abre la terminal y navega a la carpeta del proyecto.
3. Ejecuta `npm install` para instalar las dependencias.

**Iniciar la Aplicación:**
- Usa el comando `npm start` para iniciar la aplicación.
- Accede a la aplicación a través de tu navegador web en [http://localhost:3000](http://localhost:3000).

**Documentación:**
- Consulta la carpeta 'docs' para acceder a la documentación completa sobre el uso y la estructura del proyecto.

**Contribuciones:**
- ¡Contribuciones son bienvenidas! Antes de contribuir, asegúrate de seguir nuestras pautas de contribución.

**Licencia:**
- Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para obtener más detalles.

**Requisitos: Proyecto A01751694_modulo2**

**Dependencias:**
- [Google Colab](https://colab.research.google.com/): Asegúrate de tener acceso a Google Colab para ejecutar el código.
- [OpenCV (cv2)](https://pypi.org/project/opencv-python/): Biblioteca para procesamiento de imágenes.
- [NumPy](https://numpy.org/): Biblioteca para operaciones numéricas en Python.
- [Pandas](https://pandas.pydata.org/): Estructuras de datos y herramientas de análisis de datos.
- [scikit-learn](https://scikit-learn.org/): Herramientas simples y eficientes para análisis predictivo de datos.
- [TensorFlow](https://www.tensorflow.org/): Plataforma de código abierto para aprendizaje automático.
- [Matplotlib](https://matplotlib.org/): Biblioteca de visualización de datos en 2D.

**Instalación:**
1. Abre Google Colab y monta Google Drive utilizando `drive.mount('/content/drive')`.
2. Instala las dependencias necesarias en Colab utilizando `!pip install nombre_paquete`.

**Ejecución del Código:**
- Ejecuta cada celda del código secuencialmente en Google Colab.
- Asegúrate de que los conjuntos de datos y archivos necesarios estén disponibles en tu Google Drive.

**Modelo de Red Neuronal:**
- Se utiliza un modelo secuencial de TensorFlow con capas como GlobalAveragePooling2D, Dense, BatchNormalization y Dropout.
- El modelo se compila con el optimizador Adam y se configura para la clasificación.

**Entrenamiento:**
- Se utiliza ImageDataGenerator para aumentar el conjunto de datos y evitar el sobreajuste.
- Se implementan ModelCheckpoint y EarlyStopping para guardar el mejor modelo y detener el entrenamiento según la mejora.

**Visualización:**
- Los resultados y métricas del entrenamiento se visualizan utilizando Matplotlib.

**Notas:**
- Asegúrate de tener suficiente espacio de almacenamiento en Google Drive para guardar modelos y datos generados durante el entrenamiento.

Espero que esta descripción sea útil. ¿Hay algo más en lo que pueda ayudarte?