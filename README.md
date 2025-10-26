# 🚢 Titanic Data Analysis Project

## 📖 Overview
This project performs **exploratory data analysis (EDA)** on the famous **Titanic dataset (Titanic.csv)**.  
The goal is to uncover meaningful insights related to passenger survival and visualize patterns through various graphs and charts.

---

## 🎯 Objectives
The main insights drawn from this analysis are:
1. **Survival Counts** – Total number of survivors vs non-survivors.  
2. **Survival Rate by Gender** – Comparison of male and female survival percentages.  
3. **Survival Value by Gender** – Numerical analysis of survival distribution between genders.  
4. **Correlation Matrix** – Relationship between numerical features like Age, Fare, Pclass, and Survival.

Additionally, the data is visualized using **matplotlib** and **seaborn** for better understanding.

---

## 🧠 Steps Involved

### 1. Importing Libraries
```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```
### 2. Loading the Dataset
```
data = pd.read_csv("Titanic.csv")
```
### 3. Data Exploration
```
data.head()
data.info()
data.describe()
data.isnull().sum()
```
### 4. Data Cleaning
  Filled missing values in Age and Embarked.
  Dropped irrelevant columns like Cabin (if too many missing values).
  Converted categorical variables for analysis.
## Data Analysis & Visualization
1. Survival Counts
2. Survival Rate by Gender
3. Survival Value by Gender
4. Correlation Matrix
### How to Run
  1. Clone the repository or download the .ipynb / .py file.
  2. Ensure Titanic.csv is in the same directory.
  3. Install dependencies:
       ``` pip install pandas numpy matplotlib seaborn```
  4. Run the script in Jupyter Notebook or any Python IDE.
### Conclusion
Through this analysis, we explored how gender, passenger class, and fare impacted survival on the Titanic.
Data visualization helped transform raw CSV data into clear, actionable insights — demonstrating the power of Python for data analysis and storytelling.
