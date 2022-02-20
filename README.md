# Heart-Disease

In this project, we will be using the [Heart Disease Data](https://archive.ics.uci.edu/ml/datasets/Heart+Disease) from the UCI Machine Learning Repository. The purpose of this project is to create a classification (Machine Learning) model to predict the presence of heart disease in patients given their features. We will use several different classification algorithms on a set of simulated samples that is reflective of the real dataset. We will attempt at optimizing the classification algorithms by using common model fitting techniques such as QR decomposition, LU decomposition, and helosky's Decompositions, therefore, we will construct each algorithm from scratch. 

## Content of the Dataset
The data set use in this project contains information on 303 patients and their attributes. For the purpose of this project, only 14 out of the 76 attributes will be use to build our classification model.


| Attributes  | Descriptions | Characteristic |
| --- | --- | --- |
|  age  | age in years   | integer  | 
| sex  | sex (1 = male; 0 = female)   | integer  |
| cp  | chest pain type: 1: typical angina ,  2: atypical angina, 3: non-anginal pain, 4: asymptomatic   | integer | 
| trestbps | resting blood pressure (in mm Hg on admission to the hospital | integer  |
| chol  | serum cholestoral in mg/dl  | integer  | 
| fbs  | (fasting blood sugar &gt; 120 mg/dl) (1 = true; 0 = false)  | integer |
| restecg  | resting electrocardiographic results: 0: normal, 1: having ST-T wave abnormality, 2: showing probable or definite left ventricular hypertrophy by Estes' criteria  | integer | 
| Content Cell  | Content Cell  | Content Cell  |
| Content Cell  | Content Cell  | Content Cell  | 
| Content Cell  | Content Cell  | Content Cell  |
| Content Cell  | Content Cell  | Content Cell  | 
| Content Cell  | Content Cell  | Content Cell  |
| Content Cell  | Content Cell  | Content Cell  | 
| Content Cell  | Content Cell  | Content Cell  |


## Components of the Project:
- Data Cleaning 
- Explanatory Analysis and Data Normlaization
- Least Square Method
  1. QR Decomposition
  2. LU Decomposition
  3. Chelosky's Decompositions
- Data Simulations (Training Data Set)
- Model Building/Model Selection (Will run our models using the simulated dataset, and we will then pick the model that has the best accuracy rate to run on the real dataset.)
  1. Logistic Regression
  2. Linear Discriminant Analysis
  3. Newton's Algorithm
- Conclusion (Results and Visualization)

