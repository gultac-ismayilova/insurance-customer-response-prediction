# Insurance Customer Response Prediction & Risk Scoring

##  Project Overview

This project analyzes insurance customer data to predict whether a customer will respond to a marketing offer.

The goal is to help insurance companies identify high-potential customers and improve targeting strategies.

---

##  Dataset

* ~380,000 customer records
* Features include:

  * Age
  * Gender
  * Vehicle Age
  * Vehicle Damage
  * Annual Premium
  * Previously Insured

---

##  Key Steps

### 1. Data Cleaning

* Checked for missing values (none found)
* Removed duplicate records (~0.07%)

### 2. Exploratory Data Analysis (EDA)

* Identified strong patterns in customer behavior
* Found that **Vehicle Damage** is a key predictor

### 3. Feature Engineering

* Encoded categorical variables
* Prepared data for modeling

### 4. Modeling

* Built a Logistic Regression model
* Handled class imbalance using class_weight

### 5. Model Evaluation

* Focused on recall for the positive class
* Achieved high recall (~0.98), ensuring most potential customers are identified

---

##  Key Insights

* Customers with vehicle damage are **~45x more likely** to respond
* Previously insured customers are less likely to respond
* Vehicle age also impacts response behavior

---

##  Risk Scoring System

Instead of only predicting 0/1, a **risk score (probability)** was created:

* Low Risk
* Medium Risk
* High Risk

This allows better business decision-making and customer targeting.

---

##  Business Value

* Helps optimize marketing campaigns
* Improves customer targeting
* Reduces wasted outreach efforts
* Supports data-driven decision making

---

##  Tools Used

* Python (Pandas, NumPy)
* Scikit-learn
* Matplotlib / Seaborn

---

##  Future Improvements

* Add advanced models (XGBoost, LightGBM)
* Build interactive dashboards (Power BI)
* Improve feature engineering

---

##  Author

Gultaj Ismayilova
