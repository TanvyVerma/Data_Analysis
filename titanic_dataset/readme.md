# 🚢 Titanic Survival Analysis – Exploratory Data Analysis (EDA)

## 📖 Project Overview

This project focuses on performing an in-depth Exploratory Data Analysis (EDA) on the Titanic dataset to understand the factors influencing passenger survival.

The objective was **not to build a predictive model**, but to deeply analyze patterns, relationships, and feature interactions that impact survival outcomes.

This project helped strengthen my fundamentals in:
- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Correlation Analysis
- Categorical Encoding
- Insight Extraction

---

## 🛠️ Tools & Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📊 Dataset Information

The dataset contains passenger details such as:
- PassengerId
- Pclass
- Name
- Sex
- Age
- SibSp (Siblings/Spouses aboard)
- Parch (Parents/Children aboard)
- Fare
- Embarked
- Survived (Target Variable)

---

## 🔎 Key Steps Performed

### 1️⃣ Data Cleaning
- Handled missing values
- Checked data types
- Performed initial exploratory summaries

### 2️⃣ Feature Engineering

Created a new feature:

**Family_size = SibSp + Parch**

Then categorized passengers into:

- `Alone`
- `Small Family`
- `Large Family`

This helped in analyzing how family size affects survival probability.

---

### 3️⃣ Categorical Encoding

Applied one-hot encoding to:
- Pclass
- Sex
- Embarked
- Family_type

Converted boolean columns into integer format for better correlation analysis.

---

### 4️⃣ Correlation Analysis

Generated correlation heatmaps to understand:
- Relationships between numerical features
- Interaction between engineered features and survival
- Multicollinearity between variables

---

## 📈 Key Insights

- Passengers in **1st class** had significantly higher survival rates than those in 3rd class.
- **Females** had much higher survival probability compared to males.
- **Younger passengers** were more likely to survive.
- Higher **Fare** was positively associated with survival.
- Passengers traveling in **small families** had better survival chances than those traveling alone or in large families.
- Embarkation port showed slight variation in survival distribution.

---

## 🧠 Learning Outcomes

Through this project, I improved my understanding of:

- How to derive meaningful features from raw data
- Interpreting correlation matrices critically
- Understanding interaction effects instead of isolated analysis
- Structuring a complete EDA pipeline

---

## 🚀 Future Improvements

- Apply statistical hypothesis testing
- Build baseline models (Logistic Regression)
- Compare model performance with and without engineered features
- Perform feature importance analysis

---

## 📂 Repository Structure

```
titanic_dataset/
│
├── Titanic_EDA.ipynb
├── Dataset files
└── README.md
```

---

## 📌 Conclusion

This project strengthened my analytical thinking and foundational data science skills. It demonstrates a structured approach to understanding real-world datasets before moving toward modeling.

---

👩‍💻 Created by Tanvy Verma  
Second-Year Computer Science Student  
Aspiring Machine Learning Engineer
