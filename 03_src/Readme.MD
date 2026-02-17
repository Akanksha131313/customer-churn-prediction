**SRC Folder README – Telecom Churn Prediction Project :**

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**Overview -**

• This folder contains the full pipeline for Telecom Customer Churn Prediction, implemented in Python. The project predicts customers at high risk of churn, identifies key drivers, and provides actionable business insights to improve retention strategies.

• It is organized into three modules -

a) 01_data_processing.py – Handles data upload, cleaning, encoding categorical features and target variable, and train-test split.

b) 02_model_evaluation.py – Evaluates trained models using accuracy, classification report, confusion matrix, and optional visualizations.

c) 03_model_training.py – Implements Logistic Regression pipeline, integrates preprocessing, model training, evaluation, feature importance analysis, and dynamic business insights.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------

**Key Features Across Modules -**

• Data Preprocessing: Converts numeric columns, handles missing values, encodes categorical features, splits dataset into training and testing sets.

• Model Training: Logistic Regression pipeline with StandardScaler and class_weight='balanced' to handle real-world class imbalance.

• Evaluation & Metrics: Accuracy, classification report, confusion matrix, and visualizations for clear recruiter-friendly output.

• Feature Importance: Extracts top drivers of churn from model coefficients to highlight business impact.

• Business Insights & Recommendations: Dynamic metrics like churn rate, short-tenure churn, top features, and actionable steps for retention strategy.

• HR/ATS Optimized: Clear headings, bullet points, and keywords for ATS compliance like churn prediction, Logistic Regression, feature importance, retention strategy, telecom.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

**How to Run -**

• Place telecom_churn_dataset_utf8.csv in the data folder.

• Execute 01_data_processing.py to clean and prepare data.

• Run 03_model_training.py to train model, evaluate, and generate dynamic insights.

• Optionally, call 02_model_evaluation.py functions to visualize performance metrics.

• Outputs are formatted for recruiter-friendly, quick scan, highlighting business impact, not just code.

**ATS-Friendly Keywords -**

telecom, churn prediction, Logistic Regression, feature importance, class imbalance, accuracy, classification report, confusion matrix, retention strategy, predictive model, customer churn
