# Sleep-health-and-lifestyle-Prediction
Sleep health and lifestyle Prediction for Sleep Disorder (Classification Model)
This repository contains a Jupyter notebook that demonstrates how to build a machine learning model to predict sleep disorders based on sleep health and lifestyle factors.

Data

The data used in this project is the Sleep_health_and_lifestyle_dataset.csv dataset, which contains information on sleep health and lifestyle factors for a group of individuals. The dataset includes the following features:

Person ID
Gender
Age
Occupation
Quality of Sleep
BMI Category
Heart Rate
Daily Steps
Sleep Disorder
High Pressure
Low Pressure
Model

The model used in this project is a support vector machine (SVM) classifier. SVM is a supervised machine learning algorithm that can be used for both classification and regression tasks. In this project, we use SVM to classify individuals into three categories:

No sleep disorder
Sleep apnea
Insomnia
Results

The model achieved an accuracy of 89.19% on the test set. The F1 scores for the three classes were as follows:

No sleep disorder: 0.9189
Sleep apnea: 0.9
Insomnia: 0.8235
Usage

To use this project, you will need to have Python 3 and the following libraries installed:

pandas
numpy
sklearn
xgboost
Once you have installed the required libraries, you can run the Jupyter notebook to train and evaluate the model
