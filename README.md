# Sales-Data-Prediction
Using  tensorflow.keras and importing Sequential to perform an artificial neural network to forecast future sales

## Table of Contents

- [Project Overview](#project-overview)
- [Data Source](#data-sources)

## Project Overview
The goal of the project is to create a model for a car salesperson to estimate the purchasing power of potential customers using the Annual Salary and Car Purchased amount. We are going to deploy a regression model to predict the total USD amount customers would be willing to pay for cars. The predictions are based on various customer attributes including age, annual salary, credit, car debt and net worth.

## Data Sources 

Car_Purchased: the primary dataset used for analysis is the "Car_Purchasing_Data.csv" file, containing detailed information about client history and purchase amount.

### Tools
- Python (Data cleaning, Training and Testing)

### Libraries 
- Pandas
- Numpy
- Seaborn
- Matplotlib.pyplot
- sklearn.preprocessing import MinMaxScaler (encoding)
- sklearn.model_selection import train_test_split
- import tensorflow.keras
- from keras.models import Sequential
- from keras.layers import Dense
