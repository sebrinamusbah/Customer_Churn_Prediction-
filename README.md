
# Customer Churn Prediction 📉

A machine learning project to predict customer churn in the telecom industry, submitted as part of the Fundamentals of Machine Learning course at Arba Minch University.

---

## 🧠 Problem Statement

Customer churn results in significant revenue loss in the telecom sector. This project aims to predict whether a customer will churn using historical service usage and demographic data.

---

## 📊 Dataset

- **Source:** [Kaggle - Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Records:** 7,043 customers
- **Features:** Demographics, billing, usage, and contract details
- **Target:** `Churn` (Yes/No)

---

## ⚙️ Tools & Technologies

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 🚀 Project Structure

```
Customer_Churn_Prediction/
│
├── Customer_Churn_Prediction.ipynb        # Main Jupyter notebook with code & outputs
├── Customer_Churn_Prediction.pdf          # Exported report version
├── README.md                              # Project overview (this file)
```

---

## 📈 Models Used

- Random Forest Classifier
- Stacking Ensemble (Random Forest + SVC → Logistic Regression)

---

## ✅ Results

| Model            | Accuracy |
|------------------|----------|
| Random Forest    | 79.70%   |
| Stacking Ensemble| 80.98%   |

Key insights:
- Customers with short contracts and high monthly charges are more likely to churn.
- Ensemble methods can slightly improve churn prediction performance.

---



## 📌 Future Work

- Hyperparameter tuning
- Feature engineering
- Model deployment via Flask or Streamlit

---

## 📂 License

This project is for educational purposes only.
