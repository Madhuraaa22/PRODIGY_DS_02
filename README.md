# PRODIGY_DS_02

## 📌 Task Overview
This repository contains **Task-02** of my Data Science internship with **Prodigy InfoTech**.  
The goal of this task is to **perform data cleaning and exploratory data analysis (EDA)** on a dataset of my choice — I have used the **Titanic dataset** from Kaggle.

The main objectives are:
- Clean and preprocess the dataset.
- Explore relationships between variables.
- Identify patterns and trends in the data.


## 📊 Dataset
- **File name:** `titanic.csv`
- **Source:** [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
- **Description:** Contains passenger details such as age, gender, ticket class, fare, cabin, and survival status.


## 🛠️ Tools & Libraries Used
- **Google Colab** / **Jupyter Notebook**
- **Python** 3.x
- **Libraries:**
  - `pandas` – Data cleaning and manipulation
  - `numpy` – Numerical computations
  - `matplotlib` – Data visualization
  - `seaborn` – Statistical plots

## 🧹 Data Cleaning Steps
1. **Handle missing values**  
   - Filled missing `Age` values with median.
   - Filled missing `Embarked` with mode.
   - Dropped `Cabin` column due to excessive missing values.

2. **Data type conversion**  
   - Converted categorical features (`Sex`, `Embarked`) into numeric codes.

3. **Removing duplicates**  
   - Checked for and removed duplicate rows.

## 📊 Exploratory Data Analysis (EDA)
### 1. **Univariate Analysis**
- Distribution of passenger ages
- Count of survivors vs. non-survivors
- Passenger class distribution

### 2. **Bivariate Analysis**
- Survival rate by gender
- Survival rate by passenger class
- Fare vs. survival relationship

### 3. **Multivariate Analysis**
- Combined effect of `Sex` and `Pclass` on survival
- Age, class, and survival correlation

## 📈 Key Insights
- Women had a much higher survival rate than men.
- Passengers in **1st class** had the highest chance of survival.
- Younger passengers had slightly better survival rates.
- Higher fares were associated with higher survival rates.
