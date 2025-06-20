# 04: Python & Tooling for Machine Learning

## 📘 Overview
This file supports the hands-on Python notebook and helps develop practical fluency in the core libraries used in nearly every machine learning pipeline.

---

## 🧠 Key Concepts

- **pandas**: Library for manipulating structured data using DataFrames.
- **NumPy**: Foundation for numerical computation using arrays.
- **matplotlib & seaborn**: Tools for creating plots and visualizing data.
- **scikit-learn**: Library for ML models and utilities (e.g., `fit`, `transform`, `predict`).

---

## 📌 Common Patterns

- `df.describe()`: Gives a quick statistical summary of the dataset.
- `df.dropna()`: Removes rows with missing values.
- `df['new'] = ...`: Add engineered features to support modeling.
- `model = LinearRegression().fit(X, y)`: Fit a simple linear regression.

---

## 🎨 Analogies & Intuition

- **DataFrame**: Like a spreadsheet with Python superpowers.
- **Seaborn plots**: Like sketching the shape of your data before modeling.
- **Feature engineering**: Like giving your model a better set of tools to work with.
- **Fitting a model**: Like drawing a best-fit line through cloud of points.

---

## 🎯 Tutor Instructions

### Teaching Prompts
- “What does this plot tell us about relationships between features?”
- “What happens if we don’t clean missing data before modeling?”
- “Why is it better to work with `tip_percent` than raw tip?”

### Pop Quiz Strategy
- Ask: “What function loads a CSV?”
- Review model structure: “What happens if you call `.predict()` before `.fit()`?”

---

## 🧪 Quiz Questions (with Answers)

**Q1.** What does `df.describe()` show?  
> ✅ Summary statistics: count, mean, std, min, max, quartiles

**Q2.** Why is feature engineering helpful?  
> ✅ It makes patterns more obvious to the model (e.g., tip percentage)

**Q3.** What does `.fit()` do in scikit-learn?  
> ✅ Trains the model on the input features and target

**Q4.** What does seaborn’s `hue` argument do?  
> ✅ Colors points based on a categorical variable

---

## ✅ Summary Checklist

- [ ] I can load and inspect a dataset with pandas
- [ ] I can clean and transform data for analysis
- [ ] I can create visualizations to explore relationships
- [ ] I understand how to use `fit()` and basic scikit-learn models

---
