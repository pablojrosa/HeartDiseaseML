# Proyecto de Análisis de Enfermedades Cardíacas

Este repositorio contiene un proyecto personal basado en el conjunto de datos de enfermedades cardíacas disponible en Kaggle. El objetivo principal de este proyecto es realizar un análisis exhaustivo de los datos, desarrollar modelos de Machine Learning y desplegar el mejor modelo en producción para predecir la presencia de enfermedades cardíacas en pacientes.

## Conjunto de Datos

El conjunto de datos utilizado en este proyecto se encuentra en [Kaggle](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset). Contiene información sobre diversas características médicas y factores de riesgo de 303 pacientes, así como la presencia o ausencia de enfermedades cardíacas.

## Objetivos del Proyecto

Los objetivos principales de este proyecto son:

1. **Análisis Exploratorio de Datos (EDA)**: Explorar y comprender la estructura de los datos, identificar patrones, relaciones y posibles correlaciones entre las características y la presencia de enfermedades cardíacas.

2. **Desarrollo de Modelos de Machine Learning**: Entrenar varios modelos de Machine Learning para predecir la presencia de enfermedades cardíacas en función de las características médicas proporcionadas en el conjunto de datos.

3. **Evaluación de Modelos**: Evaluar el rendimiento de los modelos utilizando métricas relevantes como precisión, recall, F1-score, y área bajo la curva ROC (AUC-ROC).

4. **Despliegue en Producción**: Implementar el modelo con mejor rendimiento en un entorno de producción, lo que permitirá realizar predicciones en tiempo real para nuevos pacientes.

## Estructura del Repositorio

- **`data/`**: Carpeta que contiene el conjunto de datos original y cualquier otro archivo relacionado con los datos.
- **`notebooks/`**: Carpeta que contiene los notebooks de Jupyter utilizados para el análisis de datos, desarrollo de modelos y evaluación.
- **`models/`**: Carpeta que contendrá los modelos entrenados guardados en formato serializado para su uso posterior.
- **`scr/`**: Carpeta que contiene scripts de utilidad, por ejemplo, para preprocesamiento de datos o para cargar y utilizar el modelo en producción.
- **`app/`**: Carpeta que contendrá el código necesario para desplegar el modelo en producción, como una aplicación web.
- **`README.md`**: Archivo que estás leyendo ahora, proporcionando una descripción general del proyecto y cómo utilizar el repositorio.

## Requerimientos

- Python 3
- Bibliotecas de Python (se pueden encontrar en `requirements.txt`)

## Contribuciones

¡Las contribuciones son bienvenidas! Si encuentras algún error, tienes sugerencias de mejoras o deseas colaborar de alguna manera, no dudes en abrir un problema o enviar una solicitud de extracción.


cambios para test