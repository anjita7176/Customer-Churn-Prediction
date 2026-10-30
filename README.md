# 📊 Customer Churn Prediction

### End-to-End Machine Learning | Python | EDA | Scikit-learn

An end-to-end Machine Learning project that predicts whether a customer is likely to leave a telecommunications company using customer demographics, subscribed services, contract details, and billing information.

The project focuses on data preprocessing, Exploratory Data Analysis (EDA), feature engineering, model building, and performance evaluation to understand customer churn patterns.

---

## 🎯 Project Objectives

- Understand customer churn patterns through EDA.
- Clean and preprocess raw customer data.
- Identify important factors influencing customer churn.
- Build Machine Learning classification models.
- Evaluate model performance using multiple metrics.
- Generate customer churn predictions.

---

## 📁 Dataset Information

**Dataset:** IBM Telco Customer Churn

- Total Records: 7,043
- Total Features: 21
- Target Variable: `Churn`
- Problem Type: Binary Classification

**Target Classes:**
- Yes – Customer churned.
- No – Customer retained.

---

## 🛠️ Technologies & Libraries

| Technology | Purpose |
|---|---|
| Python | Programming |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Scikit-learn | Machine Learning |
| Google Colab | Development environment |
| Joblib / Pickle | Model serialization |

---

## 🔍 Project Workflow

1. Data Collection and Loading
2. Data Understanding
3. Data Cleaning and Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Selection
6. Train-Test Split
7. Feature Scaling and Encoding
8. Logistic Regression Model
9. Random Forest Classifier
10. Model Evaluation and Comparison
11. Feature Importance Analysis
12. Customer Churn Prediction
13. Model Saving and Exporting Predictions

---

## 📈 Exploratory Data Analysis

The analysis explores:

- Overall customer churn distribution.
- Customer tenure and churn relationship.
- Monthly charges and churn patterns.
- Contract type and customer retention.
- Internet service and churn behavior.
- Correlation between numerical features.

---

## 🤖 Machine Learning Models

**1. Logistic Regression**

Used as a baseline classification model to predict customer churn.

**2. Random Forest Classifier**

Used to capture complex patterns and relationships in customer data through multiple decision trees.

---

## 📊 Model Performance Comparison

Both Machine Learning models were evaluated using multiple classification metrics.

| Metric | Logistic Regression | Random Forest |
|---|---:|---:|
| Accuracy | 80.55% | 77.50% |
| Precision | 65.72% | 56.21% |
| Recall | 55.88% | 68.98% |
| F1-Score | 60.40% | 61.94% |
| ROC-AUC | 0.8421 | 0.8375 |

### 🏆 Key Findings

- Logistic Regression achieved the highest accuracy of **80.55%**.
- Logistic Regression achieved a slightly higher ROC-AUC of **0.8421**.
- Random Forest achieved better churn recall of **68.98%**.
- Random Forest achieved a slightly higher F1-Score of **61.94%**.

### Conclusion

Logistic Regression performed better in overall accuracy and ROC-AUC, while Random Forest was better at identifying actual churn customers.

The results highlight the trade-off between overall predictive performance and identifying customers who are likely to leave.

---

## 📂 Project Structure

```text
Customer-Churn-Prediction/
│
├── Customer_Churn_Prediction.ipynb
├── customer_churn_model.pkl
├── customer_churn_predictions.csv
└── README.md
```

---

## 💾 Project Outputs

- `Customer_Churn_Prediction.ipynb` – Complete project notebook.
- `customer_churn_model.pkl` – Saved trained Machine Learning model.
- `customer_churn_predictions.csv` – Customer churn prediction results.

---

## 🚀 Key Learnings

- Practical experience with an end-to-end ML workflow.
- Handling missing and inconsistent data.
- Performing Exploratory Data Analysis.
- Building preprocessing pipelines.
- Training and comparing classification models.
- Evaluating models using classification metrics.
- Saving trained models for future use.

---

## 👩‍💻 About the Project

This project is part of my Data Science and Machine Learning learning journey. It helped me gain practical experience in solving a real-world business problem using Python and Machine Learning.

**Created by:** Anjita Kumari

**GitHub:** [anjita7176](https://github.com/anjita7176)

**LinkedIn:** [Connect with me](https://www.linkedin.com/in/anjita-kumari-48975624b/)

---

⭐ If you find this project interesting, feel free to explore the repository!
