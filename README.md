# 🏚️ Industrial-copper-modeling
The copper industry, while dealing with relatively simple data on sales and pricing, often encounters challenges that can hinder accurate predictions and effective decision-making.Specifically, the project focuses on building a regression model to predict the selling price and a classification model to predict the status (WON/LOST) of leads. Additionally, an interactive Streamlit web application will be created to facilitate real-time predictions using these models.

## 💼 Domain:
🌋 Manufacturing

## 🛅Technologies Used:
* Python
* Numpy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Pickle
* Streamlit


## 🛅 Approaches:
* Python scripting,
* Data Preprocessing,
* EDA, 
* Streamlit.

## 🛅 Data Understanding:
🌋Load and understand the copper data through CSV files. Check the data for consistency and completeness.

## 🛅 Data Preprocessing:
🌋Loaded the copper CSV into a DataFrame. Cleaned and filled missing values, addressed outliers,and adjusted data types. Analyzed data distribution and treated skewness.

## 👁️‍🗨️ EDA:
Exploratory Data Analysis
🌋visualizing outliers and skewness(before and after treating skewness) using Seaborn’s boxplot, distplot, violinplot.

## Featuring Engineering:
🌋Aggregating or transforming existing features to create more informative representations of the data. And drop highly correlated columns using SNS HEATMAP.

## Model Building and Evaluation:
🌋 ML Regression model which predicts continuous variable ‘Selling_Price’.

🌋 ML Classification model which predicts Status WON or LOST

## Streamlit:
🌋 In a Streamlit page,Developed a user interface for interacting with the models. Predicted selling price and status based on user input.

## 📨 Pip install packages:
* pip install scikit-learn 
* pip install xgboost 
* pip install streamlit 
* pip install pickle
* pip install scipy
* pip install imblearn  (!- before installation)

# 💻 Import Packages:
* import pandas as pd
* import numpy as np
* import seaborn as sns
* import matplotlib.pyplot as plt
* from streamlit_option_menu import option_menu
* import pickle
* import streamlit as st

### (get the data from dataset which uploaded in our repository).
