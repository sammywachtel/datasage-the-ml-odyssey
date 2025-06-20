# 02: Probability & Statistics

## 📘 Overview
Probability is how we measure uncertainty, and statistics is how we learn from data. This file complements the notebook with concepts, derivations, visual intuition, and tutor instructions.

> 💻 **Hands-On Practice**: This theory guide pairs with [02_probability_statistics.ipynb](02_probability_statistics.ipynb) for interactive simulations and visualizations.

---

## 🧠 Key Concepts

- **Probability**: The likelihood of an event occurring.
- **Random Variable**: A variable whose outcome is determined by chance.
- **Distributions**: Functions describing how values are spread (e.g., Normal, Binomial).
- **Bayes’ Theorem**: A method to reverse conditional probabilities using priors and likelihoods.

---

## 🔍 Mathematical Derivations

### Bayes’ Theorem

Given events $A$ and $B$:

$$
P(A|B) = \frac{P(B|A) \cdot P(A)}{P(B)}
$$

This updates the belief in $A$ after seeing $B$.

---

## 🎨 Analogies & Intuition

- **Probability**: Think of it as betting odds. If a fair die lands on 4, there was a 1 in 6 chance.
- **Distributions**:
  - *Normal*: Bell curve — common in heights, test scores.
  - *Binomial*: Coin flips — count of successes over trials.
- **Bayes' Rule**: Like a medical test: initial belief + evidence reshapes what we believe.

---

## 🎯 Tutor Instructions

### Teaching Prompts
- “What is the difference between a PMF and a PDF?”
- “Walk me through Bayes’ Theorem in your own words.”
- “Why might the posterior probability be low even if the test is accurate?”

### Pop Quiz Strategy
- Ask for a real-world example of conditional probability.
- Return to older math: "What shape does the normal curve resemble?"

---

## 🧪 Quiz Questions (with Answers)

**Q1.** What does the area under a probability density function represent?  
> ✅ The total probability = 1

**Q2.** What distinguishes a Binomial distribution?  
> ✅ It models discrete trials with success/failure outcomes

**Q3.** Why do we divide by $P(B)$ in Bayes’ Theorem?  
> ✅ To normalize the probabilities — ensuring they sum to 1

**Q4.** What is the expected value of a fair six-sided die?  
> ✅ $\frac{1+2+3+4+5+6}{6} = 3.5$

---

## ✅ Summary Checklist

- [ ] I understand how to simulate a random process
- [ ] I can differentiate between discrete and continuous distributions
- [ ] I can calculate and interpret conditional probability
- [ ] I understand how Bayes’ Theorem updates belief
- [ ] I can read and interpret a probability distribution plot

---
