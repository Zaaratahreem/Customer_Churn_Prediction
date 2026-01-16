# Customer Churn Prediction (Beginner ML Project)

## Overview
This is a **beginner-level machine learning project** that predicts whether a customer will churn (leave) a telecom company. 

The main goal of this project is to **practice and demonstrate a complete ML workflow**, including data understanding, preprocessing, feature encoding, model training, and evaluation.

⚠️ **Note:** The dataset used is very small (20 entries), so the evaluation metrics are not realistic. This project is **for learning purposes only** and should **not be used for real business decisions**.

---

## Dataset
- The dataset is a small CSV file with **20 customer records** and **39 features**.  
- Features include customer demographics, service usage, subscription details, and contract information.  
- Target column: `churn_label` (Yes/No) — indicates whether a customer churned.  

**Example features:**
- `age`, `gender`, `under_30`, `senior_citizen`, `married`, `dependents`  
- `tenure_in_months`, `monthly_charge`, `total_charges`, `internet_service`  
- `contract`, `payment_method`, `churn_label`  

---

## Project Steps

1. **Data Understanding**
   - Explored the dataset: head, shape, columns, and data types
   - Checked for missing values

2. **Data Cleaning**
   - Removed unnecessary ID columns (`customer_id`, `count`)  
   - Converted numeric columns as needed  
   - Handled missing or inconsistent data

3. **Feature Engineering**
   - One-hot encoded categorical variables  
   - Prepared features (`X`) and target (`y`) for model training

4. **Model Training**
   - Split dataset into train and test sets  
   - Trained a **Logistic Regression** model

5. **Evaluation**
   - Evaluated the model using:
     - Accuracy  
     - Confusion matrix  
     - Classification report  

⚠️ **Important:** Because of the tiny dataset, the model achieved **100% accuracy**, but this is **not meaningful in a real scenario**. This is purely a demonstration of workflow.

---

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/zaaratahreem/Customer_Churn_Prediction.git

install the required python libraries
pip install pandas scikit-learn

---

Future Improvements 

Use a larger, real-world dataset to build a meaningful model

Experiment with other ML algorithms (Random Forest, XGBoost)

Analyze feature importance to understand drivers of churn

Visualize correlations, churn patterns, and distributions

Provide actionable business insights from the predictions
