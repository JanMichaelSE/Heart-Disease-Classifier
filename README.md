# Heart-Disease-Classifier

## Predicting heart disease using machine learning

This notebook looks into using python based machine learning and data scinece libraries in the attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.


Taking the following approach:
1. Problem Definition
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentation


## 1.Problem Definition

In a statement:
> Given clinical parameters about a patient, can we predict whether or not they have heart disease?


## 2.Data

The original data came from the Cleveland datbasea from the UCI Machine Learning Repository.
 * https://archive.ics.uci.edu/ml/datasets/Heart+Disease

There is also a version on Kaggle available. 
 * https://www.kaggle.com/ronitf/heart-disease-uci
 
 
## 3.Evaluation 

> If we can reach 90% accuracy at predicting whether or not a patient has heart diesease during the proof of concept, then the project should be further dived into.


## 4.Features

Information about each feature in the data.

**Data Dictionary**

* age: in years
* sex: (1 = male; 0 = female)
* cp: chest pain type
* trestbps: resting blood pressure (in mm Hg on admission to the hospital)
* chol: serum cholestoral in mg/dl
* fbs: (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
* restecg: resting electrocardiographic results
* thalach: maximum heart rate achieved
* exang: exercise induced angina (1 = yes; 0 = no)
* oldpeak: ST depression induced by exercise relative to rest
* slope: the slope of the peak exercise ST segment
* ca: number of major vessels (0-3) colored by flourosopy
* thal: 3 = normal; 6 = fixed defect; 7 = reversable defect
* target: 1 or 0


## 5. Modelling

In this step we took in consideration the following machine learning algortihms:
* Logistic Regression
* Random Forest Classifier
* KNN Classifier

During the evaluation of each models accuracy it appeared that the Logistic Regression model was resulting the best metrics. 
Note: Planning on revisiting the Random Forest Classifier to try other Hyperparams with GridSearchCV.

## 6. Experimentation
Repeat the process to find areas of improvements.
