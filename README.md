# Implementation-of-Logistic-Regression-Model-to-Predict-the-Placement-Status-of-Student

## AIM:
To write a program to implement the the Logistic Regression Model to Predict the Placement Status of Student.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Import necessary libraries
2. Load the Placement_Data.csv dataset
3. Copy the dataset and preprocess
4. Check for missing and duplicate values
5. Convert categorical variables to numerical values
6. Split dataset into features and target variable
7. Split the dataset into training and testing sets
8. Train the logistic regression model
9. Predict the output on test data
10. Evaluate the model 

## Program:
```
/*
Program to implement the the Logistic Regression Model to Predict the Placement Status of Student.
Developed by: Siva R
RegisterNumber:  212225100050
*/
from google.colab import drive
drive.mount('/content/drive')

import pandas as pd
data=pd.read_csv("drive/MyDrive/ML/Placement_Data.csv")
data.head()
```

## Output:
![the Logistic Regression Model to Predict the Placement Status of Student](sam.png)
<img width="1420" height="251" alt="image" src="https://github.com/user-attachments/assets/1d3d10ef-0ab1-4c36-9259-90adc0d0e549" />



## Result:
Thus the program to implement the the Logistic Regression Model to Predict the Placement Status of Student is written and verified using python programming.
