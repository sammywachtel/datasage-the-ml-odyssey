# 01: Linear Algebra Intro

## 📘 Overview
This file provides a conceptual and instructional guide for the AI tutor and student. It complements the Jupyter notebook with analogies, mathematical insights, and quizzing strategies.

---

## 🧠 Key Concepts
- **Vectors**: Quantities with direction and magnitude. Think of them like arrows in space.
- **Matrices**: Grids of numbers that can transform space. Imagine them as functions that stretch, rotate, reflect, or squash vectors.
- **Dot Product**: Measures alignment between two vectors. It is maximum when vectors point in the same direction.
- **Matrix Multiplication**: Combines transformations. Order matters ($AB \ne BA$).

---

## 🔍 Mathematical Derivations

### Dot Product
Given vectors **a** and **b**:

$$
\mathbf{a} \cdot \mathbf{b} = \|a\| \|b\| \cos(\theta)
$$

This equals the projection of one vector onto the other when $\theta$ is the angle between them.

### Matrix Multiplication
If $A$ is an $m \times n$ matrix and $B$ is an $n \times p$ matrix, then:

$$
C = AB \quad \text{is an } m \times p \text{ matrix}
$$

---

## 🎨 Analogies & Intuition
- **Dot Product**: Like comparing how much two people are walking in the same direction.
- **Matrix as Transformation**: Picture gridlines bending, stretching, or rotating after a matrix is applied.
- **Identity Matrix**: Like multiplying by 1; it does nothing.
- **Zero Matrix**: Like muting all output.

---

## 🎯 Tutor Instructions

### Teaching Prompts
- Ask the student: “If the dot product is zero, what can we say about the angle between the vectors?”
- Have the student sketch a 2D vector and visualize what happens when you apply a matrix that doubles x-values and halves y-values.
- Encourage drawing: “Show me what a rotation matrix does to this square.”

### Pop Quiz Strategy
- Interleave memory questions from later topics (e.g., “Can you see how the dot product comes back in neural networks?”).
- Use “what-if” questions: “What if the transformation matrix is all zeros?”

---

## 🧪 Quiz Questions (with Answers)

**Q1.** What does the dot product measure?  
> ✅ Alignment / cosine similarity between vectors

**Q2.** What is the result of dotting a vector with itself?  
> ✅ The squared magnitude of the vector

**Q3.** What kind of transformation does this matrix perform?

$$
\begin{bmatrix} 2 & 0 \\ 0 & 1 \end{bmatrix}
$$

> ✅ Horizontal stretching (x-dimension doubled)

**Q4.** Can matrix multiplication be commutative?  
> ❌ No, $AB \ne BA$ in general

---

## ✅ Summary Checklist

- [ ] I understand what vectors and matrices are
- [ ] I can compute a dot product and explain its meaning
- [ ] I can multiply two matrices and describe the geometric effect
- [ ] I can visualize matrix transformations on a 2D grid
- [ ] I can explain why $AB \ne BA$

---
