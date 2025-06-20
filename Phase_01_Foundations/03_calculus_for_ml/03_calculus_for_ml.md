# 03: Calculus for Machine Learning

## 📘 Overview
Calculus provides the mathematical tools to understand how models learn and optimize. This file complements the notebook with derivations, analogies, and instructional support.

> 💻 **Hands-On Practice**: This theory guide pairs with [03_calculus_for_ml.ipynb](03_calculus_for_ml.ipynb) for interactive gradient descent demonstrations and optimization exercises.

---

## 🧠 Key Concepts

- **Derivative**: Measures rate of change. Tells us how steep a function is at a point.
- **Gradient**: A vector of partial derivatives — shows the direction of steepest ascent.
- **Chain Rule**: Used to differentiate nested functions.
- **Gradient Descent**: An iterative algorithm that moves in the direction opposite the gradient to minimize a cost function.

---

## 🔍 Mathematical Derivations

### Derivative of a Quadratic

$$
f(x) = (x - 3)^2 \\
f'(x) = 2(x - 3)
$$

### Chain Rule Example

If $f(g(x)) = (2x + 1)^2$:

$$
f'(x) = 2(2x + 1) \cdot 2 = 4(2x + 1)
$$

---

## 🎨 Analogies & Intuition

- **Derivative**: Like measuring the slope of a hill you're standing on.
- **Gradient Descent**: A hiker taking steps downhill to reach the lowest point of a valley.
- **Learning Rate**: Step size — too small = slow, too big = overshoot or bounce.

---

## 🎯 Tutor Instructions

### Teaching Prompts
- “Can you describe in your own words what a derivative tells you about a function?”
- “What happens if the gradient is zero?”
- “Let’s graph a loss curve. Show me where the gradient would be positive or negative.”

### Pop Quiz Strategy
- Revisit earlier knowledge: “Where else have we seen slopes before?”
- Challenge: “Change the learning rate. What happens to convergence?”

---

## 🧪 Quiz Questions (with Answers)

**Q1.** What does a derivative represent?  
> ✅ The slope or rate of change of a function at a point

**Q2.** What does the gradient represent in ML?  
> ✅ The vector of slopes for each input dimension — shows how to adjust weights

**Q3.** What is the purpose of the learning rate in gradient descent?  
> ✅ Controls how big a step we take in the direction of the negative gradient

**Q4.** What happens when you use too large a learning rate?  
> ❌ The algorithm may diverge or oscillate

---

## ✅ Summary Checklist

- [ ] I understand how to compute and interpret a derivative
- [ ] I understand what a gradient is in multiple dimensions
- [ ] I can apply the chain rule
- [ ] I can visualize and explain gradient descent
- [ ] I know how learning rate affects convergence

---
