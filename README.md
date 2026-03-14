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
# Import required libraries
import pandas as pd
import numpy as np
from sklearn.model_selection import train_test_split
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import accuracy_score, confusion_matrix

# Create sample dataset
data = {
    'CGPA': [7.5, 8.2, 6.8, 9.0, 5.5, 7.0, 8.5, 6.0],
    'Internships': [1, 2, 0, 3, 0, 1, 2, 0],
    'Projects': [2, 3, 1, 4, 1, 2, 3, 1],
    'Communication': [7, 8, 6, 9, 5, 6, 8, 5],
    'Placement': [1, 1, 0, 1, 0, 0, 1, 0]
}

# Convert to DataFrame
df = pd.DataFrame(data)

# Input features
X = df[['CGPA', 'Internships', 'Projects', 'Communication']]

# Target variable
y = df['Placement']

# Split data into training and testing
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=42)

# Create Logistic Regression model
model = LogisticRegression()

# Train the model
model.fit(X_train, y_train)

# Predict placement
y_pred = model.predict(X_test)

# Evaluate model
accuracy = accuracy_score(y_test, y_pred)
cm = confusion_matrix(y_test, y_pred)

print("Predicted Placement:", y_pred)
print("Accuracy:", accuracy)
print("Confusion Matrix:\n", cm)
```

## Output:
![the Logistic Regression Model to Predict the Placement Status of Student](sam.png)
<<<<<<< HEAD
![alt text](<Screenshot 2026-03-14 100929.png>)



=======

Predicted Placement: [1 0]
Accuracy: 1.0
Confusion Matrix:
 [[1 0]
 [0 1]]
>>>>>>> 96f6b87f73ce3868625f5846d93225f6afc4678c
## Result:
Thus the program to implement the the Logistic Regression Model to Predict the Placement Status of Student is written and verified using python programming.
