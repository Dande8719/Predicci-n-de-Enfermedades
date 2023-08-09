# Predicción-de-Enfermedades (Modelo de Machine Learning / Clasificación Multiclase)

![image](https://github.com/Dande8719/Prediccion-de-Enfermedades/assets/103025222/33013b34-7386-419e-8276-5b9d1d9f0fbd)

Predicción de enfermedades en función de los síntomas presentados por el paciente. En: Illness prediction knowing the symptoms of the patient.

En este proyecto usamos un modelo de Machine Learning de clasificación multiclase para predecir enfermedades basándonos en los síntomas presentados por el paciente.

Los datos para entrenar el modelo los hemos obtenido de la base de datos Kaggle ( https://www.kaggle.com/datasets/itachi9604/disease-symptom-description-dataset?select=dataset.csv) estos datos describen 132 sintomas de 41 enfermedades.

En este repositorio de guithub podemos ver los 3 notebooks donde realizamos este modelo:

1º: EDA (Exploratory Data Analisis), donde realizamos el preprocesamiento de datos y el analissi de los mismos. De aqui obtenemos un dataframe para trabajar con el en la parte del modelo de machine learning.

![image](https://github.com/Dande8719/Prediccion-de-Enfermedades/assets/103025222/1982a108-bae0-45f8-bd80-b47c9fc3b9bb)


![image](https://github.com/Dande8719/Prediccion-de-Enfermedades/assets/103025222/09dcc76b-5702-415f-b0de-22ff19811efd)


2º: Modelo. Para el modelos de machine learning usamos todos los siguientes modelos de clasificación multiclase. Guardamos el modelo y el label encoder para usarlo en la función de predición.

  -KNeighbors Classifier
  -Radius Neighbors Classifier
  -Nearest Centroid Classifier
  -Gaussian Naive Bayes Classifier
  -Logistic Regression
  -Decision Tree Classifier
  -Random Forest Classifier
  -SVC
  -AdaBoost Classifier
  -Gradient Boosting Classifier


![image](https://github.com/Dande8719/Prediccion-de-Enfermedades/assets/103025222/355a1559-074c-40ef-9e6f-257f1f4f724a)

3º: Resultados. Para comprobar la utilidad del modelo creamos una función que nos permita introducir al usuario unos sintomar y predecirle que enfermedad padece. Preguntamos por una serie de sintomas y en función de la respuesta del usuario no predice una enfermedad.


![image](https://github.com/Dande8719/Prediccion-de-Enfermedades/assets/103025222/f3b351b2-2c44-4cd3-978a-e3aca333e0ba)




En la presentación del proyecto en powerpoint podeis ver los aspectos más relevantes del mismo.
Un saludo y para cualquier custión, !No dudéis en poneros en contacto conmigo!
PD: Si estais enfermos primero llamad al médico, no preguntéis a Google XD.
