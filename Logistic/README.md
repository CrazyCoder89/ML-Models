# 🔍 Logistic Regression

This folder contains an implementation and explanation of **Logistic Regression**, one of the simplest and most widely used algorithms for binary classification tasks in machine learning.

---

## 🧠 What is Logistic Regression?

Logistic Regression is a **supervised machine learning algorithm** used for classification problems — especially binary classification. Despite the name, it is actually used for **classification, not regression**.

It works by estimating the probability that a given input belongs to a particular class (e.g., "yes" or "no", "spam" or "not spam", etc.).

---

## 🧪 How It Works

Instead of predicting actual values like linear regression, logistic regression predicts a **probability** between 0 and 1. This is done using a special function called the **sigmoid function**, which transforms any real-valued number into a value between 0 and 1.

### 📉 Sigmoid Function

<img src="https://upload.wikimedia.org/wikipedia/commons/8/88/Logistic-curve.svg" alt="Sigmoid Function" width="400"/>

- Output close to **1** → Positive class
- Output close to **0** → Negative class
- Output around **0.5** → Uncertain

---

## ✅ Advantages

- 🔹 Simple and easy to implement
- 🔹 Efficient for small datasets
- 🔹 Outputs calibrated probabilities
- 🔹 Performs well on linearly separable data
- 🔹 Less prone to overfitting than more complex models

---

## ⚠️ Disadvantages

- 🔸 Assumes linear relationship between features and log odds
- 🔸 Can underperform when features are not linearly separable
- 🔸 Sensitive to outliers
- 🔸 Not suitable for complex, non-linear relationships unless extended (e.g., using polynomial features or kernels)

---

## 🎯 Real-World Use Cases

- 🏥 **Medical diagnosis**: Predict if a patient has a disease based on test results
- 💬 **Spam detection**: Classify emails as spam or not
- 🧑‍⚖️ **Credit scoring**: Determine the likelihood of loan default
- 🎓 **Student performance**: Predict if a student will pass or fail based on study hours, attendance, etc.
- 👮 **Fraud detection**: Classify transactions as fraudulent or legitimate

---

## 📁 Files in This Folder

| File                     | Description                                |
|--------------------------|--------------------------------------------|
| `logistic_regression.py` | Python implementation from scratch         |
| `example.ipynb`          | Jupyter Notebook example & visualization   |
| `utils.py`               | Helper functions (sigmoid, prediction, etc.) |
| `README.md`              | This documentation                         |

---

## 📚 Recommended Reading

- [Wikipedia: Logistic Regression](https://en.wikipedia.org/wiki/Logistic_regression)
- [Scikit-learn Documentation](https://scikit-learn.org/stable/modules/linear_model.html#logistic-regression)
- [StatQuest Video Explanation](https://www.youtube.com/watch?v=yIYKR4sgzI8)

---

## 🧩 Next Steps

You can enhance this project by:
- Adding regularization (L1/L2)
- Extending to multiclass classification (One-vs-Rest)
- Visualizing decision boundaries on datasets

---

## 📄 License

This project is licensed under the MIT License.
