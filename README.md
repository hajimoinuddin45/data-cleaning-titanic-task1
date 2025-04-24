# 🧼 Data Cleaning & Preprocessing – Titanic Dataset

This repository contains my work for **Task 1** of the Data Preprocessing module.  
The goal was to clean and prepare a real-world dataset (Titanic dataset) for use in Machine Learning.

---

## 📌 Objective

To learn and apply essential data preprocessing techniques including:
- Handling missing values
- Encoding categorical features
- Normalizing and standardizing numerical data
- Detecting and removing outliers
- Visualizing the dataset using Python libraries

---

## 🛠 Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn

---

## 🗂 Dataset

I used the **Titanic dataset**, which contains details of passengers including:
- Survival status
- Age
- Fare
- Gender
- Class (Pclass)
- Embarkation point

---

## 📈 Steps Performed

1. **Loaded the dataset** using Pandas and explored basic details.
2. **Handled missing values**:
   - Filled missing 'Age' with median.
   - Filled missing 'Embarked' with mode.
   - Dropped 'Cabin' due to too many missing values.
3. **Converted categorical columns** using One-Hot Encoding.
4. **Standardized numerical features** ('Age' and 'Fare') using `StandardScaler`.
5. **Detected and removed outliers** using the IQR method.
6. **Visualized data** using Seaborn boxplots.

---

## 📷 Visualizations

- Boxplots to identify outliers.
- Summary of data before and after cleaning.

---

## 📁 Files

- `titanic.csv`: Raw dataset used
- `task1_data_cleaning.ipynb`: All preprocessing code and outputs
- `README.md`: This file

---

## 🤔 What I Learned

- The importance of preprocessing before feeding data into ML models.
- How to clean and prepare messy data.
- Different strategies to handle missing values and outliers.
- Encoding techniques and scaling of features.

---

Feel free to check the notebook to see the code and results!

