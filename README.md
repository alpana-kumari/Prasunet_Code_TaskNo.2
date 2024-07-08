# Prasunet_Code_TaskNo.1

                                      Titanic Dataset Analysis 

This repository includes the analysis for the Titanic dataset from Kaggle, covering EDA and feature engineering. The Titanic dataset is a classic dataset in machine learning, including demographic information about the passengers on the ship and whether they lived or died.

Overview
The Titanic dataset contains two main files:

train.csv: A file that includes data on a subset of the passengers with their target variable, whether or not they survived.
test.csv: This CSV has the same information but excludes survival outcome. 
The main idea of the project was to get an insight into inter-relations among variables and development of patterns and trends from data; feature engineering is applied on this dataset so that it becomes more efficient for the machine learning model.

Steps and Files
EDA (Exploratory Data Analysis):

First look at your distributions of your data, missing values, and relationships between features.
Datasets visualized with plots: histograms and pair plots display the distributions and correlations.
Feature Engineering:

Impute missing values in 'Age', 'Embarked, and 'Fare' variables by median and mode, respectively
Engineer new features like 'FamilySize', 'IsAlone', and extraction of 'Title' from 'Name' so that more information gets added to the data set
Encode using one-hot encoding for categorical variables like 'Sex', 'Embarked', 'Title' so that they can feed into models.
Dropping any unhelpful columns; in this case, this is 'Name', 'Ticket', 'Cabin'—these are primitive features and add little to the models in predicting survival. 
Data Visualization:

More data relationship visualization .
Interpretation of survival rates by class, gender, age, fare with seaborn and matplotlib visualizations.
