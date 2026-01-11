# 🚢 Titanic Survival Analysis (EDA)

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on the famous **Titanic dataset** to understand the factors that influenced passenger survival during the disaster.

The notebook focuses on **data cleaning, feature analysis, statistical insights, and visual exploration** using Python.  
---

## 🧾 Dataset Description
The Titanic dataset contains passenger information such as demographics, ticket details, and survival outcomes.

### 📊 Key Features
- Passenger Class (`Pclass`)
- Sex
- Age
- Number of Siblings/Spouses (`SibSp`)
- Number of Parents/Children (`Parch`)
- Fare
- Embarked Port
- Survival Status (`Survived`)

---

## 🛠️ Tech Stack
- **Python 3**
- **Pandas** – data manipulation and preprocessing  
- **NumPy** – numerical operations  
- **Matplotlib** – data visualization  
- **Seaborn** – statistical plots  

---

## 🔍 Project Workflow

### 1️⃣ Data Loading
- Imported Titanic dataset into Pandas DataFrame  
- Initial inspection using `head()`, `info()`, and `describe()`

### 2️⃣ Data Cleaning
- Handled missing values (Age, Embarked, etc.)
- Converted categorical variables into usable formats
- Removed unnecessary columns (where applicable)

### 3️⃣ Exploratory Data Analysis
- Survival rate analysis
- Gender-wise survival comparison
- Passenger class vs survival
- Age distribution of survivors vs non-survivors
- Fare impact on survival
- Embarkation port analysis

### 4️⃣ Statistical Insights
- Survival percentage calculations
- Group-based aggregation using `groupby()`
- Correlation understanding between features

### 5️⃣ Data Visualization
- Bar plots and count plots
- Histograms and distribution plots
- Clear visual storytelling using Seaborn

---

## 📈 Key Insights
- Females had a significantly higher survival rate than males
- First-class passengers were more likely to survive
- Children had better survival chances
- Higher fares correlated with higher survival probability

---
