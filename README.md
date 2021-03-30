# Modeling Grad Admissions Data

## Introduction

With so much emphasis placed on masters degrees these days, it was interesting to me to see if we could come up with a model that could predict your chances of getting into a graduate school by simply inputting your application values.

In this project, we look at this dataset from Kaggle that provides the parameters considered important during Masters Programs admission applications (such as GRE score, undergrad GPA, TOEFL scores...), and we attempt to take those inputs and create a neural network to predict the chances of that applicant being accepted for the Masters Program.

## Dataset

Graduate Admissions

URL: https://www.kaggle.com/mohansacharya/graduate-admissions?select=Admission_Predict_Ver1.1.csv


## Model

We use a Sequential model with 1 hidden layer, and we use Mean Squared Error for our loss. 

## Summary
Our MSE and MAE were relatively low, telling us our predicted model was not too far off the actual predicted chances of admission.

It's important to note that the model only had ~500 parameters and very few datapoints. In order to produce a model with better accuracy, we should increase the number of parameters in our neural model while also increasing our initial data points.
