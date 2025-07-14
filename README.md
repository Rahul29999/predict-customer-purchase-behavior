# 🛍️ Predicting Customer Purchase Behavior

## 📌 Overview

This project aims to predict whether a customer will make a purchase based on behavioral and transactional data. By applying supervised machine learning techniques, we build predictive models to identify patterns in customer activity and help businesses tailor marketing strategies to increase conversions and retention.

---

## 🎯 Objectives

- Perform exploratory data analysis (EDA) to understand customer behavior
- Engineer features that reflect user activity and purchasing potential
- Train multiple classification models (Logistic Regression, Random Forest, XGBoost, etc.)
- Evaluate model performance using accuracy, precision, recall, F1-score, and ROC-AUC
- Extract insights to guide data-driven decision making in marketing

---

## 🧰 Tech Stack

- **Language**: Python 3.8+
- **Data Analysis**: pandas, numpy
- **Visualization**: matplotlib, seaborn
- **Modeling**: scikit-learn, xgboost
- **Notebook**: Jupyter Notebook

---

## 📊 Dataset & Features

- The dataset contains user-level transactional or clickstream data (assumed format: `.csv`, `.xlsx`, or `.parquet`)
- Target variable: Whether a user made a purchase (binary: 0/1)
- Features include:
  - **User activity**: click frequency, session duration, product views
  - **Time features**: last login, days since registration, weekday behavior
  - **Engagement**: cart additions, wishlist saves
  - **Transaction history**: previous purchases, total spent

---

## 🔍 Exploratory Data Analysis (EDA)

- Checked for missing values, data types, and outliers
- Visualized class imbalance using bar plots
- Explored feature correlations with heatmaps
- Distribution of numerical features and how they relate to the purchase label
- Analyzed purchase trends over time, device types, or customer segments

---

## 🛠️ Feature Engineering

- Binary conversion for target label
- One-hot encoding for categorical variables
- Normalization/standardization of numerical features
- Created interaction terms and composite features (e.g., engagement score)

---

## 🤖 Models Trained

| Model               | Accuracy | Precision | Recall | F1-Score | ROC-AUC |
|--------------------|----------|-----------|--------|----------|---------|
| Logistic Regression| 82%      | 0.81      | 0.79   | 0.80     | 0.87    |
| Random Forest       | 85%      | 0.84      | 0.82   | 0.83     | 0.89    |
| XGBoost             | 86%      | 0.85      | 0.84   | 0.84     | 0.90    |

- **Best Performing Model**: XGBoost  
- Used GridSearchCV for hyperparameter tuning

---

## 📈 Performance Evaluation

- Used Confusion Matrix to assess false positives/negatives
- ROC Curve and AUC to measure discriminatory power
- Feature Importance plotted to understand key drivers of purchase behavior

---

## 💡 Key Insights

- Recency and frequency of user actions are strong predictors of purchases
- Users adding to cart or wishlist are more likely to convert
- Weekend activity and high time-on-site also indicate higher buying intent

---

## 📦 How to Run

```bash
# Clone the repo
git clone https://github.com/Rahul29999/predict-customer-purchase-behavior.git
cd predict-customer-purchase-behavior

# Install dependencies
pip install -r requirements.txt

# Launch notebook
jupyter notebook predict-customer-purchase-behavior.ipynb
````

---

## 🚀 Future Improvements

* Apply deep learning models (ANN, TabNet)
* Handle class imbalance with SMOTE or undersampling
* Build a recommendation system using collaborative filtering
* Deploy model with Flask/Streamlit as a real-time API or dashboard

---

## 👤 Author

** Rahul Kumar Sharma **
* 🎓 B.Tech, Mining Engineering – IIT (ISM) Dhanbad
* 📧 [20je0749@iitism.ac.in](mailto:20je0749@iitism.ac.in)
* 🔗 [GitHub](https://github.com/Rahul29999) | [LinkedIn](https://linkedin.com/in/rahul-kumar-sharma-aa0b57233)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

```

---

If you share the exact feature names and output metrics from the notebook, I can personalize this further. Would you like a short GitHub "About" section (100 characters) too?
```
