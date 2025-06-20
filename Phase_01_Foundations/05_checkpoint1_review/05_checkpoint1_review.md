# 05: Checkpoint 1 Review

## 📘 Overview
This review is your bridge between foundational concepts and real-world machine learning. It reinforces understanding, strengthens connections across topics, and prepares you for the classical ML models you'll encounter next.

---

## 🧠 Comprehensive Topic Recap

### 🔹 01: Linear Algebra
- **Vectors** are quantities with direction and magnitude.
- **Dot Product** measures alignment: maximum when vectors point the same direction.
- **Matrix Multiplication** combines linear transformations.
- **Transformations** like stretch, rotation, and reflection are applied using matrices.

### 🔹 02: Probability & Statistics
- **Probability** quantifies uncertainty.
- **Distributions** describe how values are spread (e.g., Normal, Binomial).
- **Bayes’ Theorem** updates beliefs based on evidence:
  $$
  P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}
  $$

### 🔹 03: Calculus
- **Derivatives** show the rate of change of a function.
- **Chain Rule** is used to differentiate nested functions.
- **Gradient Descent** moves in the direction of steepest decrease to minimize loss.

### 🔹 04: Python Tooling
- Use `pandas` for data wrangling, `NumPy` for arrays, `matplotlib/seaborn` for visualizing.
- `scikit-learn` is your go-to toolkit for model fitting, preprocessing, and evaluation.

---

## 🧪 Full Review Quiz (15 Questions)

**Q1.** What is the result of dotting a vector with itself?  
> ✅ The square of its magnitude

**Q2.** What does matrix multiplication represent geometrically?  
> ✅ Composition of transformations

**Q3.** In a standard Normal distribution, what proportion of values fall within 1 standard deviation of the mean?  
> ✅ ~68%

**Q4.** What is the difference between a PDF and a CDF?  
> ✅ PDF gives density at a point; CDF gives cumulative probability up to that point

**Q5.** What does the derivative of a function represent?  
> ✅ Its instantaneous rate of change

**Q6.** What is the derivative of $f(x) = (x - 3)^2$?  
> ✅ $f'(x) = 2(x - 3)$

**Q7.** What does the gradient vector point toward in optimization?  
> ✅ The direction of steepest ascent

**Q8.** What happens if your learning rate is too small?  
> ✅ Convergence is very slow

**Q9.** What does `df.dropna()` do?  
> ✅ Removes rows with missing values

**Q10.** What does `.fit()` do in a scikit-learn model?  
> ✅ It trains the model using the provided data

**Q11.** Why is feature engineering important?  
> ✅ It provides the model with more informative inputs

**Q12.** What does Bayes' Theorem help you compute?  
> ✅ Posterior probability based on prior and evidence

**Q13.** Which Python library is best for matrix operations?  
> ✅ NumPy

**Q14.** What is a DataFrame in pandas?  
> ✅ A 2D table-like data structure with labeled axes

**Q15.** What happens to a vector when multiplied by a rotation matrix?  
> ✅ Its direction changes, but its length stays the same (if matrix is orthonormal)

---

## 🧭 Concept Mapping Task

Try drawing this network of dependencies:

```
[Linear Algebra]
    → Dot Product
    → Matrix Ops
        → Gradient Descent ← Calculus ← Chain Rule
        → Transformations → Data Representations

[Probability]
    → Distributions
    → Bayes’ Rule → Reasoning Under Uncertainty
        → Logistic Regression (coming soon!)

[Python Tooling]
    → Data Cleaning → Feature Engineering
    → Visualization → Insight Discovery
```

---

## 🎯 Tutor Instructions

### High-Level Prompts
- “Which ideas from linear algebra show up in gradient descent?”
- “How do probability and calculus combine in machine learning?”
- “Explain Bayes’ Rule in a way a friend could understand.”

### Active Review Ideas
- Recreate visualizations: matrix transformations, PDFs
- Re-derive gradients from scratch with student narration
- Ask: “How would you teach this to someone else?”

---

## ✅ Mastery Checklist

- [ ] I understand and can explain vectors, dot products, and matrix multiplication
- [ ] I can describe how gradient descent works and why the chain rule is needed
- [ ] I understand conditional probability and Bayes' Theorem
- [ ] I can clean, explore, and visualize real-world datasets using Python
- [ ] I can use scikit-learn to fit simple regression models

---

🎉 You're ready to begin Phase 2: Classical Machine Learning. Take a deep breath — you’ve built a rock-solid foundation. Let’s go! 🚀


---

## 🧠 Interview Memory Test Questions

These questions are designed to test recall and fluency for common technical interviews.

**Q1.** Write a NumPy function to compute the dot product of two vectors.  
> ✅ Use `np.dot(a, b)` or `a @ b` if both are 1D arrays.

**Q2.** Write out the formula for Bayes’ Theorem.  
> ✅ $P(A|B) = \frac{P(B|A) P(A)}{P(B)}$

**Q3.** Use the chain rule to differentiate $f(g(x)) = (2x + 1)^2$.  
> ✅ $df/dx = 4(2x + 1)$

**Q4.** What does `df.describe()` return?  
> ✅ Count, mean, std, min, max, and quartiles for numeric columns

**Q5.** What are the steps in gradient descent?  
> ✅ Initialize → Compute gradient → Update → Repeat until convergence

---

### 🎯 Tutor Instructions

- Have the student write out answers to Q1–Q5 before revealing the solution.
- Ask: “Can you explain this out loud as if you're in a whiteboard interview?”
- Reframe questions: “Instead of code, explain what `df.describe()` is doing logically.”

---

