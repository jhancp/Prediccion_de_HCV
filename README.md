![Header](https://user-images.githubusercontent.com/70854575/230533809-f2cb6b9c-459e-4498-a637-6ff79f86f969.jpg "Header")

## Descripción 😊

Este proyecto corresponde a mi trabajo final en el [Programa de Especialización en Análisis de Datos con Python de Data Science Research Perú](https://drive.google.com/file/d/1DOwuVodwuh-Ec_fF-qsiCSzIvVybSMgY/view?usp=sharing). Tuvo como objetivo principal el poder servir de apoyo para detectar a donadores de sangre infectados con el virus de hepatitis C. Como lenguaje de programación se escogió Python. 

El dataset utilizado se encuentra en el UC Irvine Machine Learning Repository, el cual se presenta acontinuación: 

[HCV data Data Set](https://archive.ics.uci.edu/ml/datasets/HCV+data) 

Te preguntarás, ¿Cómo puedo detectar el virus de hepatitis C en las muestras de sangre de donantes?

Para responder dicha pregunta, este proyecto constó de tres etapas importantes:

**Etapa N°1:** Consistió en la realización del análisis exploratorio de los datos, esto implica la limpieza e imputación de datos, el análisis de las variables categóricas y numéricas, así como el análisis de correlación entre dichas variables, esto último es importante para encontrar la relación directa entre la enfermedad y algún compuesto de la sangre.

**Etapa N°2:** Consistió en la trasformación y preparación de los datos, esto implicó la definición del formato de los datos así como el balanceo de los mismos para finalmente dividir el dataset en dos grupos. Para ello, se aplicó el principio de Pareto, el cual recomienda distribuir el 80% para el entrenamiento y 20% para la validación. Esto con el fin de evitar que el modelo de predicción implementado al ser entrenado pueda sufrir de sobreajuste, también llamado overfitting.

**Etapa N°3:** Consistió en el entrenamiento y validación de modelos de los predicción implementados en el proyecto, para esta ocasión fueron los modelos de Regresión Logística, KNN y Random Forest. Finalmente, se realizó una comparación entre estos modelos, para conocer cuál es el que mejor se adecua a los datos de este proyecto.

Como conclusiones se puede indicar:

1. Evaluando los 3 modelos de predicción utilizados se puede decir que Random Forest es el modelo más idóneo para este caso, dado su nivel de accuracy es el más alto de los 3 modelos evaluados, el cual hace referencia a cuan bien puede predecir.

2. A pesar de que Regresión Logistica es el modelo con menor exactitud entre los 3 modelos de predicción utilizados, se puede indicar que es idóneo en el caso de que se quiera utilizar para identificar pacientes que padecen Cirrosis.

3. Es necesario balancear el dataset debido a que cantidad de datos que tenia una clase era una  muy superior a las otras, esto podría traer como consecuencias que el algoritmo implementado no pueda predecir adecuadamente y caer en overfitting. 

4. Como mejora futura se puede proponer enfocar esta investigación en la detección de pacientes con cirrosis, utilizando como variable principal la enzima AST, dado que esta encima tiene mucha relevancia en la salud del hígado. Así como también se podría cambiar el enfoque y buscar detectar si el donante puede estar contagiado de VHC utilizando el Cociente AST/ALT.

A continuación les comparto el enlace del proyecto para que lo puedas revisar: 

[Predicción de HCV](https://github.com/jhancp/Prediccion_de_HCV/blob/main/Prediccion_VHC.ipynb) 

## Autor ✒️
**Jhan Carlos Caya Pérez**

[![linkedin](https://img.shields.io/static/v1?label=&message=linkedin&color=0e76a8&logo=linkedin&logoColor=white&style=for-the-badge)](https://www.linkedin.com/in/jhancp/)

## Contacto
Si quieres contactarme, puedes escribirme a jhan.cayap@gmail.com 

## Licencia 📄
MIT Public License v3.0
No puede usarse comercialmente.
