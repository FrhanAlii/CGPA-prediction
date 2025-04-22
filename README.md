**🎓 Student GPA Prediction System (Regression-Based)**

This project presents a comprehensive machine learning pipeline to predict Semester GPA of university students using a variety of data transformations and regression techniques. It explores different preprocessing strategies—original data, log-transformation, and Z-score normalization—and compares their influence on predictive model performance.

**📁 Repository Contents**

File/Notebook	Description
students_responses_main.csv	Raw student data including demographic, behavioral, and academic features.
log_transormed_etc.rar	Archived version of transformed datasets and possibly additional assets.
Regression_gpa_with_all_freatures_orginal_data.ipynb	Regression model using original, untransformed student data.
Regression_gpa_all_feature_z_score.ipynb	Regression model using Z-score normalized features.
Regreesion_gpa_all_features_log_transformed.ipynb	Regression model using log-transformed features to reduce skewness.

**🎯 Project Objective**

Predict students' Semester GPA based on available features.

Apply multiple data preprocessing techniques:

No transformation (raw/original features)

Log transformation (to handle skewness)

Z-score normalization (standardization)

Evaluate the performance of different regression models and feature engineering strategies.

**📊 Dataset Overview**

Each student record contains:

Academic info: attendance, CGPA, lab scores, assignment scores

Behavioral metrics: discipline, learning style, motivation level

Demographics: gender, age, background, etc.

The target variable is the Semester GPA.

**🧪 Notebooks Summary**

Regression_gpa_with_all_freatures_orginal_data.ipynb
Uses raw features as-is.

Baseline for performance comparison.

Regreesion_gpa_all_features_log_transformed.ipynb
Applies log transformation to numerical features.

Aims to reduce skewness and improve model generalization.

Regression_gpa_all_feature_z_score.ipynb
Standardizes features using Z-score normalization.

Helps bring all features to a similar scale.

**🛠️ Tools & Libraries**

pandas, numpy – Data handling

sklearn – Modeling and preprocessing

matplotlib, seaborn – Visualization

xgboost – Advanced regression modeling

**📈 Model Evaluation Metrics**

Models are evaluated using:

R² Score – Goodness of fit

MAE (Mean Absolute Error) – Average magnitude of errors

MSE / RMSE (Mean/Root Mean Squared Error) – Penalize larger errors
