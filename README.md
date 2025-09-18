# Exploratory Data Analysis on Titanic Dataset

## 📌 Project Overview
This project focuses on performing **Exploratory Data Analysis (EDA)** on the Titanic dataset. The goal is to understand the dataset, clean and preprocess the data, and explore patterns, correlations, and insights related to passengers' survival.

## 📂 Dataset
The dataset contains information about passengers on the Titanic, including:
- Passenger demographics (age, gender, class, etc.)
- Travel details (ticket, cabin, embarkation point)
- Survival status

Dataset Source: [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

## 🛠️ Tools and Libraries
The analysis is implemented using **Python** with the following libraries:
- `pandas` → Data manipulation
- `numpy` → Numerical computations
- `matplotlib` & `seaborn` → Data visualization
- `scikit-learn` → Basic preprocessing

## 🔍 Steps in EDA
1. **Data Loading & Inspection**
   - Importing dataset
   - Checking shape, datatypes, and missing values

2. **Data Cleaning & Preprocessing**
   - Handling missing values (Age, Embarked, Cabin)
   - Encoding categorical variables

3. **Univariate Analysis**
   - Distribution of Age, Fare, Pclass, etc.

4. **Bivariate & Multivariate Analysis**
   - Survival rate vs. gender, class, age group
   - Correlation heatmap

5. **Visualization**
   - Count plots, histograms, boxplots
   - Survival comparison across groups

## 📊 Key Insights
- Females had a higher survival rate compared to males.
- Passengers in **1st class** were more likely to survive than those in 2nd and 3rd classes.
- Younger passengers (children) had higher survival chances.
- High fare values correlated with higher survival probability.

