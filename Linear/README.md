# 📈 Linear Regression — From Scratch

A clean, minimal implementation of **Simple Linear Regression** using only Python and NumPy. No scikit-learn or other ML libraries—just the core math, code, and visualization you need to understand how it all works.

---

## 🧠 What Is Linear Regression?

Linear Regression models the relationship between a **dependent variable** \(y\) and a **single independent variable** \(x\) by fitting a straight line:

\[
\hat{y} = w\,x + b
\]

- **\(w\)** (weight/slope) controls the steepness of the line  
- **\(b\)** (bias/intercept) shifts the line up or down  

We choose \(w\) and \(b\) to minimize the **Mean Squared Error (MSE)**:

\[
J(w, b) = \frac{1}{n} \sum_{i=1}^{n} \bigl(y_i - \hat{y}_i\bigr)^{2}
\]

Using **Gradient Descent**, parameters are updated iteratively:

\[
w \;\;:=\;\; w - \alpha \,\frac{\partial J}{\partial w}, 
\quad
b \;\;:=\;\; b - \alpha \,\frac{\partial J}{\partial b}
\]

Where:

\[
\frac{\partial J}{\partial w}
= -\frac{2}{n} \sum_{i=1}^{n} x_i \,(y_i - \hat{y}_i), 
\quad
\frac{\partial J}{\partial b}
= -\frac{2}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)
\]

---

## ✅ Advantages

- **Simplicity & Interpretability**  
  Easy to implement and interpret—coefficients directly show feature influence.  
- **Fast Training**  
  Closed-form solution exists (Normal Equation) and gradient descent converges quickly.  
- **Baseline Benchmark**  
  Provides a solid baseline before employing more complex models.  
- **Low Variance**  
  Tends to underfit rather than overfit; more robust when data is limited.

---

## ❌ Disadvantages

- **Linearity Assumption**  
  Cannot capture non-linear relationships.  
- **Sensitive to Outliers**  
  Squared error penalizes large deviations heavily.  
- **Feature Scaling Required**  
  Gradient descent can converge slowly if features aren’t normalized.  
- **Single-Variable Limitation**  
  This implementation handles only one feature—extending to multiple requires additional code.

---

## 🎯 Common Use Cases

- **Economics & Finance**  
  Predicting housing prices, stock returns, or consumer spending.  
- **Biology & Medicine**  
  Modeling dosage–response curves, growth rates.  
- **Engineering**  
  Estimating material fatigue, sensor calibration.  
- **Education & Social Sciences**  
  Analyzing test scores vs. study time, demographic trends.

---

## 📂 Folder Contents

