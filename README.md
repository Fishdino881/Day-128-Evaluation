# Day-128-Evaluation

###  Overview

Day 128 focuses on **Model Evaluation**, a crucial step in Machine Learning used to measure how well a model performs on unseen data.

Evaluation helps determine:

* Accuracy of predictions
* Reliability of the model
* Areas for improvement

---

##  What is Model Evaluation?

Model evaluation is the process of testing a trained model using evaluation metrics and validation techniques.

It helps answer:
- Is the model accurate?
- Is it overfitting or underfitting?
- Can it generalize to new data?

---

##  Evaluation Workflow

```text id="eval1"
Trained Model → Test Data → Predictions → Metrics → Performance Analysis
```

---

##  Common Evaluation Metrics

### Classification Metrics

#### 1️ Accuracy

Measures correct predictions.

```text id="eval2"
Accuracy = Correct Predictions / Total Predictions
```

---

#### 2️ Precision

Measures how many predicted positives are actually correct.

---

#### 3️ Recall

Measures how many actual positives are identified correctly.

---

#### 4️ F1 Score

Balance between precision and recall.

---

### 🔹 Regression Metrics

#### 1️ MAE (Mean Absolute Error)

#### 2️ MSE (Mean Squared Error)

#### 3️ RMSE (Root Mean Squared Error)

#### 4️ R² Score

---

## ⚙️ Example (Python)

```python id="eval3"
from sklearn.metrics import accuracy_score

accuracy = accuracy_score(y_test, predictions)

print("Accuracy:", accuracy)
```

---

##  Validation Techniques

- Train-Test Split
- Cross-Validation
- Confusion Matrix

---

##  Common Problems

* Overfitting
* Underfitting
* Data leakage

---

##  Why Evaluation Matters?

* Ensures model reliability
* Helps compare algorithms
* Improves decision-making

---

##  Key Takeaways

- Evaluation measures model performance
- Metrics vary based on problem type
- Essential before deployment

---

