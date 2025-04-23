# SCT_DS_02

# 🚢 Titanic Dataset - Data Cleaning and Exploratory Data Analysis (EDA)

This project involves **data cleaning** and **exploratory data analysis** on the famous [Titanic dataset](https://www.kaggle.com/competitions/titanic/data) from Kaggle. The goal is to explore and understand the key variables that might have influenced survival, uncover patterns, and identify trends in the data.

---

## 📌 Objective

- Clean and preprocess the Titanic dataset.
- Explore and visualize relationships between features.
- Identify patterns and trends that contribute to survival.
- Generate insights for further predictive modeling.

---

## 🗂️ Dataset Description

The dataset includes information on passengers aboard the Titanic such as:

- `PassengerId`
- `Survived` (0 = No, 1 = Yes)
- `Pclass` (Ticket class: 1st, 2nd, 3rd)
- `Name`
- `Sex`
- `Age`
- `SibSp` (Number of siblings/spouses aboard)
- `Parch` (Number of parents/children aboard)
- `Ticket`
- `Fare`
- `Cabin`
- `Embarked` (Port of Embarkation)

---

## ⚙️ Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 EDA Tasks Performed

### 1. 🔧 Data Cleaning
- Handled missing values in `Age`, `Cabin`, and `Embarked`.
- Converted categorical variables (`Sex`, `Embarked`) to numeric using encoding.
- Removed or transformed irrelevant columns (`Ticket`, `Name`).

### 2. 🔍 Univariate Analysis
- Visualized distributions of age, fare, and survival.
- Count plots for categorical variables like sex, class, and embarked.

### 3. 📈 Bivariate & Multivariate Analysis
- Survival vs Age, Sex, Class
- Heatmap of feature correlations
- Grouped statistics (e.g., survival rate by gender and class)

### 4. 📌 Insights Discovered
- Females had a much higher survival rate.
- Passengers in 1st class had better survival chances than those in 3rd class.
- Younger passengers had slightly higher chances of survival.
- Most people embarked from Southampton.

---

## 🧪 Sample Visualizations

- **Countplot:** Survival counts by gender and class
- **Histplot** Age distribution with survival overlay
- **Box Plot:** Embarkation point distribution

---

## 🚀 How to Run

1. Download the dataset from Kaggle: [Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)
2. Place `train.csv` in your project directory.
3. Run the notebook or script:
   ```bash
    titanic_eda.ipynb
