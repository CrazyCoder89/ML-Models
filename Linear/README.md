# 📈 Linear Regression — From Scratch

A clean, minimal implementation of **Simple Linear Regression** using only Python and NumPy. No scikit-learn or other ML libraries—just the core math, code, and visualization you need to understand how it all works.

---

## 🧠 What Is Linear Regression?

Linear Regression models the relationship between a **dependent variable** \(y\) and a **single independent variable** \(x\) by fitting a straight line:

\[
\hat{y} = wx + b
\]

- **\(w\)** (weight/slope) controls the steepness of the line  
- **\(b\)** (bias/intercept) shifts the line up or down  

## Mean Squared Error (MSE)
- Measures the average squared difference between predictions and actual values, highlighting larger errors.  
- Provides a smooth, differentiable metric that’s easy to optimize and interpret.  
- Lower MSE indicates a tighter fit and better overall model performance.  

## Gradient Descent
- Iteratively updates model parameters to minimize the loss by moving “downhill” on the error surface.  
- Controlled by a learning rate that balances update size and convergence stability.  
- Scales effectively to large datasets and high-dimensional problems.  

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
