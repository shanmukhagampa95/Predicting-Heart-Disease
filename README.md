# [A] HeartDisease_Prediction-
To anticipate how likely, it is that people will Effect  HeartDisease or not. We'll also compare the accuracy of different models and choose the best one.

## [B]Problem Statement:

It aims to model and predict the presence of heart disease in patients by using binary classification machine learning algorithms.
The project involved analysis of the heart disease patient dataset with proper data processing. Then, different models were trained and and predictions are made with different algorithms KNN, Decision Tree, Random Forest,Adaboost,xgboost,Logistic Regression This is the jupyter notebook code and dataset I've used for my Kaggle kernel 'Binary Classification with Sklearn'

I've used a variety of Machine Learning algorithms, implemented in Python, to predict the presence of heart disease in a patient. This is a classification problem, with input features as a variety of parameters, and the target variable as a binary variable, predicting whether heart disease is present or not.

## [C]Machine Learning algorithms used:

1. Logistic Regression 
2. Adaboost
3. K-Nearest Neighbours 
4. Decision Tree
5. Random Forest 
6. XGBoost 

## [d] Dataset:
Dataset used: https://www.kaggle.com/ronitf/heart-disease-uci

UCI Heart Disease Dataset (https://archive.ics.uci.edu/ml/datasets/Heart+Disease?spm=5176.100239.blogcont54260.8.TRNGoO)

## [E] Program:

We have to setup some methods/steps that we will be following to get our desired results:

1.Exploratory Data Analysis

2.About the models

3.Comparing the model results

4.Selection of the best model

## [F] Exploratory Data Analysis:
In this step we will be loading and cleaning the data. Cleaning which will involve missing value treatment, dropping the unwanted variables, changing categorical variables to machine understandable format, dummy variable creation, graphical interpretation and splitting the data set into train and test.

## Loading Dataset: The dataset consists of 303 rows and 14 columns.
age: The person's age in years

gender: The person's sex (1 = male, 0 = female)

cp(Chest Pain Type): The chest pain experienced (Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic)

trestbps: The person's resting blood pressure (mm Hg on admission to the hospital)

chol: The person's cholesterol measurement in mg/dl

fbs(fasting_blood_sugar): The person's fasting blood sugar (> 120 mg/dl, 1 = true; 0 = false)

restecg: Resting electrocardiographic measurement (0 = normal, 1 = having ST-T wave abnormality, 2 = showing probable or definite left ventricular hypertrophy by Estes' criteria)

thalach: The person's maximum heart rate achieved

exang: Exercise induced angina (1 = yes; 0 = no)

ldpeak: ST depression induced by exercise relative to rest ('ST' relates to positions on the ECG plot. See more here)

slope: the slope of the peak exercise ST segment (Value 1: upsloping, Value 2: flat, Value 3: downsloping)

ca: The number of major vessels (0-3)

thal: A blood disorder called thalassemia (3 = normal; 6 = fixed defect; 7 = reversable defect)

target: Heart disease (0 = no, 1 = yes)
## Dataset:

![data_set](https://user-images.githubusercontent.com/89099026/151878896-4d4d3bd0-fece-40ca-b840-4ed7a0a3ccc7.PNG)

## Data types check:
is it object ,float or int.

![check data type](https://user-images.githubusercontent.com/89099026/151878976-2a88d54a-ec94-45b0-886a-9f7b34cfa53c.PNG)

## Data Preparation:

. Missing Value Treatment: There was no null value present in data set.

![null value check](https://user-images.githubusercontent.com/89099026/151879024-c21823ee-e4dd-4ec1-8f76-db73f3b8de2d.PNG)

## Describe the data:

![describe dataset](https://user-images.githubusercontent.com/89099026/151879073-118a45b1-6e0d-453a-ae99-e9197ec32cd0.PNG)

## outlier Treatment:

Not Present any high outliers..

![outlier check](https://user-images.githubusercontent.com/89099026/151879146-fc70c4c3-e9af-40cc-ac12-e9ace55fa901.PNG)


## correlation check:

not present any high correlated value-

![corr](https://user-images.githubusercontent.com/89099026/151879213-ec0c667a-c3e9-4ad4-84f6-13599ff20f44.PNG)

## scalling Normalization:

![scalling](https://user-images.githubusercontent.com/89099026/151879262-3b204e60-9d46-4b81-8d30-f72bb2937095.PNG)

## I apply multiple model of machine Learnig and get best accuracy:

.If:-
1. train>test=overfit

2. train<test=underfit

3. train~=test=generalised

i did same thing in each algoriyhm such as :

a. Built a simple model

i. Divided the dataset in 80:20 ratio

ii. Built the model on train set and predict the values on test set
 
## Best accuracy i got after applying multiple model is Adaboost:- Adaboost	for train 0.867769 and Test 0.852459

## In Bar graph Visulation...

![multiple_model_accuracy](https://user-images.githubusercontent.com/89099026/151872705-4c5a53d5-14ff-403c-8bc2-fe6bdd84f589.jpg)

## In Detail:-

![all model accuracy in word](https://user-images.githubusercontent.com/89099026/151874476-1a13255f-4d26-445f-bf66-d19e1df923bb.PNG)

