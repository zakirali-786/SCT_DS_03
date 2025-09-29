# SCT_DS_03
PREDICTION BASED ANALYSIS

# 📊 Bank Marketing Campaign Prediction

This repository contains a machine learning project that predicts whether a customer will subscribe to a term deposit (`y`) based on their demographic and behavioral data.  
The dataset is the **Bank Marketing Dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing).
---

## 📌 Objective

The main goals of this project are to:

- Explore and analyze customer demographic and behavioral data.  
- Perform **data preprocessing** (handling missing values, encoding, scaling).  
- Build and evaluate **classification models** to predict term deposit subscription (`y`).  
- Compare models and identify the most effective one.  

---

## 🗂️ Dataset Details

- **Source:** UCI Machine Learning Repository  
- **Number of records:** ~45,000  
- **Target variable:**  
  - `y` → Has the client subscribed to a term deposit? (yes/no)  

- **Features:**
  - `age`: Customer’s age  
  - `job`: Job type  
  - `marital`: Marital status  
  - `education`: Education level  
  - `default`: Credit in default (yes/no)  
  - `balance`: Average yearly account balance (in euros)  
  - `housing`: Has housing loan?  
  - `loan`: Has personal loan?  
  - `contact`: Type of communication contact  
  - `day`: Last contact day of the month  
  - `month`: Last contact month of the year  
  - `duration`: Duration of the last contact (seconds)  
  - `campaign`: Number of contacts performed during this campaign  
  - `pdays`: Days since the client was last contacted (-1 means never)  
  - `previous`: Number of contacts performed before this campaign  
  - `poutcome`: Outcome of the previous campaign  

---

## ⚙️ Project Workflow

1. **Exploratory Data Analysis (EDA):**
   - Studied the distribution of features  
   - Visualized demographic and financial trends  
   - Correlation analysis  

2. **Data Preprocessing:**
   - Missing value handling  
   - Label encoding & one-hot encoding  
   - Feature scaling  

3. **Model Building:**
   - Decision Tree Classifier   
   - Other models (optional)  

4. **Model Evaluation:**
   - Accuracy, Precision, Recall, F1-Score  
   - Confusion Matrix  
   - ROC-AUC curve  

---

## 📈 Results

- **Best Model:** Decesion tree Classifier (example, update with your result)  
- **Key Features Impacting Prediction:**
  - `duration`  
  - `pdays`  
  - `previous`  
  - `campaign`  

The final model provides a balance of accuracy and interpretability, helping identify potential customers for bank term deposits.  
