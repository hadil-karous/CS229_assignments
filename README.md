# 🧠 CS229 Assignments — Machine Learning Implementation Repository

### 📘 Overview

This repository, **CS229_assignments**, is a personal collection of machine learning assignments inspired by **Stanford’s CS229: Machine Learning (Andrew Ng)**.

Each folder focuses on a key **principle of ML**, implemented from scratch using **Python, NumPy, Matplotlib, and SciPy** — to build intuition about how algorithms really work under the hood.

---

## 📂 Repository Structure

| Folder                       | Concept                | Description                                                                                                                |
| ---------------------------- | ---------------------- | -------------------------------------------------------------------------------------------------------------------------- |
| **linear_regression/**       | 🔢 Linear Regression   | Predicts continuous values — e.g., restaurant profit, house prices. Includes gradient descent and normal equation methods. |
| **logistic_regression/**     | 🧩 Logistic Regression | Binary classification examples: predicting student admission and microchip test validity, with and without regularization. |
| *(More folders coming soon)* | 📈                     | Each folder will cover a new concept such as SVMs, neural networks, PCA, etc.                                              |

---

## 🎯 Learning Objectives

Through these implementations, I aim to:

* Understand the **mathematical foundations** behind ML algorithms.
* Learn to **implement models from scratch** using NumPy.
* Visualize results and decision boundaries with Matplotlib.
* Experiment with **regularization** and **optimization** to prevent overfitting.
* Build a reusable base for future deep learning projects.

---

## 🧮 Technologies Used

* **Python 3**
* **NumPy** — for numerical computations
* **Matplotlib** — for visualization
* **SciPy** — for optimization (`fmin_bfgs`, etc.)

To install dependencies:

```bash
pip install numpy matplotlib scipy
```

---

## 🚀 How to Run an Assignment

Each folder contains:

* A `.py` implementation file (or multiple scripts).
* A dataset (`.txt` files).
* A `README.md` explaining the concept and the results.

To run an assignment, simply:

```bash
cd folder_name
python main_script.py
```

Example:

```bash
cd logistic_regression
python ex2.py
```

---

## 🧩 Example: Logistic Regression

This example includes:

* `ex2.py`: Predicts if a student will pass based on two exam scores.
* `ex2_reg.py`: Regularized logistic regression for microchip quality prediction.
* [Regularization Explained (PDF)](logistic_regression/RegularizationExplained.pdf): A concise document explaining the theory behind regularization.

---

## 📚 Inspiration

These assignments are inspired by:

* **Stanford CS229: Machine Learning**
* **Andrew Ng’s Coursera Machine Learning Course**

All code is **written from scratch** to reinforce deep understanding.

---

## ✨ Author

**Hadil Karous**
🎓 Engineering Student — Passionate about Machine Learning & Data Science
📍 Tunisia
📧 [GitHub Profile](https://github.com/hadil-karous)
