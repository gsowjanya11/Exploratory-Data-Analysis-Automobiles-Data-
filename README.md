# Exploratory Data Analysis on Automobile Dataset
## 📌 Overview
This project performs an Exploratory Data Analysis (EDA) on an automobile dataset to uncover meaningful insights. The analysis focuses on understanding data distributions, identifying relationships between features, and preparing the dataset for downstream modeling tasks such as automobile price prediction.

## 📂 Dataset
Source: Automobile dataset (downloaded from GitHub)

## Features include:

make (manufacturer)

fuel-type

aspiration

num-of-doors

body-style

drive-wheels

engine-location

wheel-base, length, width, height

curb-weight

engine-type, num-of-cylinders, engine-size

horsepower, peak-rpm

city-mpg, highway-mpg

price

## 🔍 Exploratory Data Analysis Steps
### 1. Data Cleaning :
Handle missing values (? replaced with NaN, imputed or dropped).

Convert categorical variables to appropriate data types.

Normalize numerical features where necessary.

### 2. Univariate Analysis
Histograms and boxplots for numerical features.

Count plots for categorical features.

### 3. Bivariate Analysis
Correlation heatmap for numerical variables.

Scatter plots

Grouped bar plots 

### 4. Multivariate Analysis
Pairplots to visualize multi-feature relationships.

Regression plots for key predictors of price.

### 💡 Key Insights
Engine size, horsepower, curb weight, and city fuel consumption show a strong correlation with automobile price.


## 🧰 Tech Stack
Python 3.x

Pandas, NumPy for data manipulation

Matplotlib, Seaborn for visualization

Jupyter Notebook for interactive analysis
