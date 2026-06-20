# Procesamiento de Lenguaje Natural 1

Repositorio con los desafíos prácticos de la materia Procesamiento de Lenguaje Natural, parte de la Carrera de Especialización en Inteligencia Artificial (CEIA) de la Facultad de Ingeniería de la UBA (FIUBA).

Cada desafío se resuelve en un notebook de Jupyter independiente, pensado para ejecutarse en Google Colab.

## Contenido

**Desafío 1** (`Desafio_1.ipynb`): clasificación de texto sobre el dataset 20 Newsgroups. Incluye vectorización con TF-IDF, análisis de similaridad coseno entre documentos y entre palabras, un enfoque de clasificación zero-shot, y modelos de Naive Bayes (MultinomialNB y ComplementNB) optimizados con GridSearchCV. Se reportan métricas F1 y conclusiones sobre el desempeño comparado de los distintos enfoques.

A medida que avance la materia, se irán agregando los desafíos siguientes con la misma estructura.

## Cómo ejecutar los notebooks

Los notebooks están pensados para abrirse directamente en Google Colab desde GitHub: basta con abrir el archivo `.ipynb` correspondiente y usar la opción "Abrir en Colab", o subirlo manualmente a Colab. Las dependencias necesarias (scikit-learn, pandas, numpy, entre otras) se instalan dentro de cada notebook según se necesiten.

## Tecnologías

Python, scikit-learn, pandas, numpy y Jupyter/Google Colab como entorno de trabajo.
