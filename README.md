# SCT_DS_03
PREDICTION BASED ANALYSIS
Bank Marketing Campaign Prediction

This project focuses on building a predictive model to determine whether a customer will subscribe to a term deposit (y) based on demographic and behavioral data. The dataset used is the Bank Marketing Dataset from the UCI Machine Learning Repository
.
📌 Objective

The goal of this project is to:

Explore customer demographic and behavioral data.

Perform data preprocessing and feature engineering.

Train classification models to predict customer subscription (y).

Evaluate model performance using accuracy, precision, recall, and F1-score.

🗂️ Dataset

Source: UCI Machine Learning Repository

Features:

age: Customer age

job: Type of job

marital: Marital status

education: Level of education

default: Has credit in default?

balance: Average yearly account balance (in euros)

housing: Has housing loan?

loan: Has personal loan?

contact: Type of communication contact

day: Last contact day of the month

month: Last contact month of the year

duration: Last contact duration (in seconds)

campaign: Number of contacts performed during this campaign

pdays: Days passed since last contact (-1 means never)

previous: Number of contacts before this campaign

poutcome: Outcome of the previous campaign

Target (y): Has the client subscribed to a term deposit? (yes/no)

⚙️ Steps Performed

Exploratory Data Analysis (EDA):

Distribution of numerical and categorical features

Correlation analysis

Insights from customer demographics

Data Preprocessing:

Handling missing values

Encoding categorical variables

Feature scaling (if needed)

Modeling:

Logistic Regression

Decision Tree / Random Forest

Other classification models

Evaluation:

Confusion matrix

Accuracy, Precision, Recall, F1-score

ROC-AUC curve

📈 Results

The model was able to predict customer subscription with reasonable accuracy.

Best performing model: [Add your best model here, e.g., Random Forest]

Key influencing features: duration, pdays, previous, campaign
