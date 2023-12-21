# Proyecto de Detección de Spam URL

## Descripción
Este proyecto implementa un modelo de aprendizaje automático para la detección de spam en URLs. Utiliza técnicas de procesamiento de lenguaje natural (NLP) y una máquina de vectores de soporte (SVM) para clasificar URLs como spam o no spam.

## Instalación

Para instalar las dependencias necesarias, clona el repositorio y ejecuta el siguiente comando en tu entorno local:

pip install -r requirements.txt
Requisitos
Python 3.6+
Bibliotecas: pandas, regex, nltk, scikit-learn (incluidas en requirements.txt)

# Uso

Sigue estos pasos para ejecutar el proyecto:

Preprocesamiento de Datos: Los datos se cargan y se limpian para eliminar duplicados y caracteres no deseados.

Procesamiento de Texto: Se aplica la lematización y la eliminación de stopwords a los textos de las URLs.

Extracción de Características: Se utiliza TF-IDF para convertir el texto en un formato numérico adecuado para el modelo.

Entrenamiento del Modelo: El modelo SVM se entrena con los datos procesados.

Optimización de Hiperparámetros: Se utiliza GridSearchCV para encontrar los mejores hiperparámetros para el modelo SVM.

Evaluación del Modelo: Se evalúa la precisión del modelo antes y después de la optimización.

#Ejecución de Scripts
Para ejecutar el script principal, usa el siguiente comando:

python app.py

# Contribución
Las contribuciones son bienvenidas. Si deseas contribuir al proyecto, por favor:

Haz un fork del repositorio.
Crea una rama para tu característica (git checkout -b feature/fooBar).
Haz tus cambios y confírmalos (git commit -am 'Add some fooBar').
Sube tu rama (git push origin feature/fooBar).
Crea una nueva solicitud de extracción (Pull Request).
Licencia
Este proyecto está licenciado bajo MIT License - vea el archivo LICENSE.md para más detalles.
