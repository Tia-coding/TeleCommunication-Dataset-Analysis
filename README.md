# Telecommunication Customer Analysis & Prediction of IBM Dataset

This project focuses on analyzing telecommunication customer data and building machine learning models to predict customer outcomes (such as churn or classification targets). It includes data preprocessing, feature engineering, encoding techniques, and applying classification models to improve predictive performance.

# Objective of this project
1. Analyze telecom customer data.
2. Perform data preprocessing and data cleaning.
3. Apply encoding techniques (Label Encoding & One-Hot Encoding).
4. Train classification models.
5. Evaluate model performance using appropriate metrics. 

NOTE: The data set of the following analysis has been attached.

# Data Preprocessing
1. Finding columns with missing values then handelling them.
2. Removed irrelevant/high-null columns.
3. Converted categorical data into numerical form.  
 Applied:
  - Label Encoding  
  - One-Hot Encoding  
4. Scaled features using StandardScaler.  

# Data Interpretation 
1.Encoded categorical variables  
2.Standardized numerical features  
Now the datset is clean and ready to be trained. 

---

# Models Used:
# Logistic Regression
1. Used as a baseline model.  
2. Simple and interpretable.  
3. Effective for binary classification.  

# Random Forest Classifier
1. Handles non-linear relationships.
2. Works well with structured data.  
3. Provides better performance than baseline.  

# Evaluation Metrics
1. Accuracy Score is used for both models and thus we can make a conclusion that both are similar but Logistic Regression has better accuracy score that RF
---

# Observations
1. Logistic Regression provided a strong baseline and better model for this dataset.
2.  Random Forest improved prediction accuracy thus it also can be used.

# Overall Analysis
1. Data preprocessing and encoding significantly improved performance.  
2. One-Hot Encoding helped handle categorical variables effectively.  
3. Logistic Regression helped in understanding feature relationships.  
4. Random Forest captured complex patterns better.  

# Libraries Used:
- Pandas  
- NumPy  
- Scikit-learn:
  - LabelEncoder  
  - StandardScaler  
  - train_test_split  
  - Pipeline  
  - LogisticRegression  
  - RandomForestClassifier  
  - Metrics:
    - accuracy_score  
# NOTE: 
I have Included the analysis with both OneHotEncoding and LabelEncoding, just using 2 ways to convert categorical data to numeric.

# Key Takeaway
This project demonstrates how preprocessing, encoding techniques, and machine learning models can be used to analyze telecom customer data and build effective predictive systems.
