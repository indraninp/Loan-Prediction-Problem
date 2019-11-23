# Loan-Prediction-Problem

## Introduction

In this project we have analysed a dataset containing customer data from a fictional financial company. The company deals with loan applications from its customers and wants to automate the loan eligibility process (real time) based on the customer details. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History, Property Area, etc. We have performed EDA and used machine learning to predict if a customer is eligible for a loan from the company, that is, whether or not their loan application will be approved.

The data is typical of what one would see for an organization dealing in home loans. It includes the following information of the customer:

Gender               
Marital Status            
Number of Dependents           
Education            
Employment type     
Income         
Loan Amount           
Loan Term     
Credit History       
Property Area, etc .


## Project Description:

The input data is cleaned, wrangled and then Exploratory Data Analysis is performed using python and its libraries. We checked for trends between the loan approval status and different features like Gender, Marital Status, Number of Dependents, Education, Employment type, etc. Presented findings with relevant statistics and visualizations using the matplotlib and seaborn libraries.

We then built prediction models using different machine learning algorithms to predict if a loan will be approved or not. For this purpose, we split our dataset into train and test sets in 70:30 ratio. The model is built using data from the train set, and is tested using data from the test set to check its accuracy. The accuracy score of each model is then calculated.

## Technologies Used

Python

Libraries: pandas, matplotlib, seaborn, sklearn

Jupyter Notebook

## Results

We gained some insights on the relation of different features like customer's Gender, Marital Status, Number of Dependents, Education, Employment type, etc on their loan approval status. Using these features different models are built using machine learning algorithms Logistic Regression, SVM, Decision Tree, Random Forest, to predict whether a loan will be approved or not. The accuracy score of each model is calculated separately.

