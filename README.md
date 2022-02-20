# Heart-Disease

In this project, we used the [Heart Disease Data](https://archive.ics.uci.edu/ml/datasets/Heart+Disease) from the UCI Machine Learning Repository. The purpose of this project is to create a classification (Machine Learning) model to predict the presence of heart disease in patients given their features. We will be constructing the classification algorithms from scratch using common model fitting techniques to optimize the efficiency and computational complexity of the algorithms. To check if our methods work correctly, we will test each method using a simulated dataset to observe if it will produce the results we want it to. 


## Content of the Dataset
The data set use in this project contains information on 303 patients and their attributes. For the purpose of this project, only 14 out of the 76 attributes will be use to build our classification model.

<details><summary>Table of Attributes</summary>
<p>

| Attributes  | Descriptions | Characteristic |
| --- | --- | --- |
|  age  | age in years   | integer  | 
| sex  | sex (1 = male; 0 = female)   | integer  |
| cp  | chest pain type: 1: typical angina , 2: atypical angina,3: non-anginal pain, 4: asymptomatic   | integer | 
| trestbps | resting blood pressure (in mm Hg on admission to the hospital | integer  |
| chol  | serum cholestoral in mg/dl  | integer  | 
| fbs  | (fasting blood sugar &gt; 120 mg/dl) (1 = true; 0 = false)  | integer |
| restecg  | resting electrocardiographic results: 0: normal, 1: having ST-T wave abnormality, 2: showing probable or definite left ventricular hypertrophy by Estes' criteria  | integer | 
| thalach | maximum heart rate achieved  | integer  |
| exang  | exercise induced angina (1 = yes; 0 = no)  | integer  | 
| oldpeak  | ST depression induced by exercise relative to rest  | float  |
| slope  | the slope of the peak exercise ST segment: 1: upsloping, 2: flat, 3: downsloping | integer  | 
| ca | number of major vessels (0-3) colored by flourosopy | integer  |
| thal | 3 = normal; 6 = fixed defect; 7 = reversable defect  | integer  | 
| target  | the predicted attribute: 0 = absence , 1 = presence | integer  |

</p>
</details>
  
## Components of the Project:
- Data Cleaning 
- Explanatory Analysis and Data Normlaization
- Least Square Method
  1. QR Decomposition
  2. LU Decomposition
  3. Chelosky's Decompositions
- Model Building
   1. Logistic Regression
   2. Linear Discriminant Analysis
   3. Newton's Algorithm
- Data Simulations (Check if our methods work correctly)
  - Split simulated data into training and testing
  - Check if each of our constructed algorithm works correctly
- Model Selection
  - Split the data into training and testing sets and train the model for each of the method.
  - Run the training set through each model and select the model with the best accuracy result.
- Conclusion (Results and Visualization)

