# Home Credit Virtual Internship Experience

## Goal
Predict potential customers who experience credit payment difficulties

## Objectives
- Develop a machine learning model to predict potential default clients 
- Create credit scorecard for loan approval

## Dataset
There are 7 datasets available in this project containing applicants data, credit card history and previous credit in Credit Bureau and Home Credit. We can obtained the dataset [here](https://www.kaggle.com/competitions/home-credit-default-risk/data)

## The Steps Involved
Here is the list of the steps involved in the notebook to achieve the goal.

**1. Data Exploration** <br>
First, we will explore the data to understand the meaning of each column in the dataset, find any patterns and gain insight from the data.

**2. Data Preprocessing** <br>
There are several steps we do during the preprocessing:
- Data Cleaning: we will ensure the data is clean from missing values and duplicates data
- Split Data: we will split the data into train set and test set
- Feature Selection: we will Identify the most suitable feature for modeling
- Feature Engineering: we will create new categorical feature based on Weight of Evidence 

**3. Modeling** <br>
Here, we will create, compare, and evaluate our machine learning models. We will use Logistic Regression then interpreted the result into a credit scorecard.
