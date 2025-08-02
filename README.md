# PRODIGY_DS_02
# Task-02: Data Cleaning and Exploratory Data Analysis (EDA) – Titanic Dataset

## 🎯 Objective
To perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset and identify meaningful patterns, trends, and relationships between variables.

---

## 📁 Dataset
- Source: [Prodigy InfoTech GitHub – Task 2](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%202)
- File used: `train.csv`
- Data includes passenger details such as age, gender, class, fare, and survival status.

---

## 🧹 Data Cleaning Steps
- Handled missing values in `Age` by filling with the median.
- Filled missing `Embarked` values with the most frequent port.
- Dropped the `Cabin` column due to excessive missing data.
- Converted string/categorical columns to numerical only where appropriate.
- Ensured the dataset was ready for correlation and visualization.

---

## 📊 Exploratory Data Analysis (EDA)
Visualizations created:
1. **Survival Count** – Overall survival distribution.
2. **Survival by Gender** – Compared male vs female survival.
3. **Survival by Passenger Class** – First, second, and third class survival rates.
4. **Age Distribution** – Histogram of age data.
5. **Correlation Heatmap** – Explored relationships between numerical variables.

---

## 🧰 Tools & Libraries Used
- Python
- Google Colab
- Pandas
- Matplotlib
- Seaborn

---

## 📌 Key Insights
- Female passengers had a higher survival rate than males.
- First-class passengers were more likely to survive.
- Younger passengers had slightly better survival chances.
- Fare and class were moderately correlated with survival.

---

## 📂 Repository Structure
