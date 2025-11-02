## 🧠 Logistic Regression & Regularized Logistic Regression

### 📄 Description

This project contains two exercises inspired by the **Andrew Ng CS229 / Coursera Machine Learning** assignments.
It demonstrates how **logistic regression** and **regularization** can be used for binary classification tasks.

---

### 🧩 Files Overview

| File                           | Description                                                                                                          |
| ------------------------------ | -------------------------------------------------------------------------------------------------------------------- |
| `ex2.py`                       | Implements logistic regression to predict whether a student passes or fails based on two exam scores.                |
| `ex2_reg.py`                   | Implements regularized logistic regression to determine if a microchip should be accepted based on two test results. |
| `ex2data1.txt`                 | Dataset for the student admission problem.                                                                           |
| `ex2data2.txt`                 | Dataset for the microchip quality control problem.                                                                   |
| `regularization_explained.pdf` | A short explanation of regularization and why it helps prevent overfitting.                                          |

---

### ⚙️ What Each Exercise Does

#### **Exercise 1 — Student Admission Prediction**

* **Goal:** Predict if a student will be admitted based on two exam scores.
* **Model:** Logistic Regression (without regularization).
* **Key steps:**

  * Visualize data.
  * Implement sigmoid, cost function, and gradient.
  * Optimize parameters using `scipy.optimize.fmin_bfgs`.
  * Plot the decision boundary.
  * Evaluate accuracy and admission probability.

#### **Exercise 2 — Microchip Quality Control**

* **Goal:** Predict whether a microchip passes QA tests.
* **Model:** Logistic Regression **with regularization** to handle non-linear decision boundaries.
* **Key steps:**

  * Feature mapping (up to degree 6 polynomial).
  * Implement regularized cost and gradient.
  * Optimize with `fmin_bfgs`.
  * Plot a curved decision boundary.
  * Compare training accuracy with different λ (lambda) values.

---

### 🧮 Dependencies

Make sure to install these libraries before running the scripts:

```bash
pip install numpy matplotlib scipy
```

---

### 🚀 How to Run

Run each file in your terminal or any IDE (e.g., VSCode, Jupyter Notebook, or Colab):

```bash
python ex2.py
python ex2_reg.py
```

Make sure the data files (`ex2data1.txt`, `ex2data2.txt`) are in the same directory.

---

### 📘 References

* Andrew Ng — *Machine Learning (Coursera / Stanford CS229)*
* [Regularization Explained (PDF)](logistic_regression/Regularization%20Explained.pdf)

---

### ✨ Author

**Hadil Karous**
🎓 Engineering Student — Passionate about Machine Learning and Data Science
📍 Tunisia
