# Proyecto-data

<img width="1081" height="720" alt="image" src="https://github.com/user-attachments/assets/4db5a932-1f45-430a-ad8c-7bd5f5fdd43a" />

Data Scientist:
SUAREZ BONAHORA FLAVIA


🤖 Predicción de Enfermedades Cardíacas


Descripción del Problema

Dominio del Problema
Las enfermedades cardiovasculares son la principal causa de muerte a nivel mundial, representando aproximadamente el 31% de todas las muertes globales según la OMS. La detección temprana de factores de riesgo cardiovascular es crucial para la prevención y el tratamiento oportuno.

En este trabajo, asumo en el rol de un científico de datos trabajando para un centro de investigación médica que busca desarrollar un sistema de apoyo a la decisión clínica. El objetivo es analizar datos clínicos de pacientes para:

- Predecir la presencia de enfermedad cardíaca

- Predecir el nivel de colesterol

Contexto

El hospital cuenta con registros históricos de pacientes que incluyen variables como edad, sexo, tipo de dolor torácico, presión arterial, niveles de colesterol, electrocardiogramas, y el diagnóstico final de presencia o ausencia de enfermedad cardíaca.

Se aplicará el proceso completo de Knowledge Discovery in Databases (KDD) para extraer conocimiento útil de estos datos y construir modelos predictivos que puedan asistir a los profesionales de la salud.

Objetivos del Trabajo:

- Aplicar el proceso KDD completo
- Implementar y comparar modelos de regresión para predecir valores de colesterol
- Implementar y comparar modelos de clasificación para detectar enfermedades cardíacas
- Evaluar modelos usando múltiples métricas de calidad
- Seleccionar y justificar el mejor modelo para cada tarea

Dataset:

Utilizarás el Heart Disease UCI Dataset, disponible públicamente en:

- Kaggle:https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset

- UCIMLRepository: https://archive.ics.uci.edu/ml/datasets/heart+disease

Variables del Dataset:

| Variable   | Descripción                                                                 | Tipo       |
|------------|------------------------------------------------------------------------------|------------|
| age        | Edad del paciente                                                           | Numérica   |
| sex        | Sexo (1 = masculino; 0 = femenino)                                           | Categórica |
| cp         | Tipo de dolor torácico (0-3)                                                 | Categórica |
| trestbps   | Presión arterial en reposo (mm Hg)                                           | Numérica   |
| chol       | Colesterol sérico (mg/dl)                                                    | Numérica   |
| fbs        | Azúcar en sangre > 120 mg/dl (1 = verdadero; 0 = falso)                      | Categórica |
| restecg    | Resultados electrocardiográficos en reposo (0-2)                             | Categórica |
| thalach    | Frecuencia cardíaca máxima alcanzada                                         | Numérica   |
| exang      | Angina inducida por ejercicio (1 = sí; 0 = no)                               | Categórica |
| oldpeak    | Depresión del ST inducida por ejercicio                                      | Numérica   |
| slope      | Pendiente del segmento ST de ejercicio máximo                                | Categórica |
| ca         | Número de vasos principales coloreados por fluoroscopia (0-3)               | Numérica   |
| thal       | 1 = normal; 2 = defecto fijo; 3 = defecto reversible                         | Categórica |
| target     | Presencia de enfermedad cardíaca (1 = sí; 0 = no)                            | Categórica |

Estructura del Notebook:

- Título y Descripción
- Importación de Librerías
- Carga de Datos
- Análisis Exploratorio (EDA)
- Preprocesamiento y Transformación
- Modelado de Regresión
- Modelado de Clasificación
- Comparación de Modelos
- Conclusiones
- Formato de Entrega

Recursos Adicionales:

Documentación de Scikit-learn:
https://scikit-learn.org/

Proceso KDD: Fayyad, U., et al. (1996). "From Data Mining to Knowledge Discovery in Databases"

Métricas de evaluación: https://scikit-learn.org/stable/modules/model_evaluation.html



