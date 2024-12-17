Sleep Disorder Prediction System Using Machine Learning
This repository contains the implementation and documentation of a Sleep Disorder Prediction System developed as a group project for the CSE445 course at North South University, under the supervision of Assistant Professor Riasat Khan. The project uses machine learning techniques to predict various sleep disorders, including insomnia and sleep apnea, based on patient data.

Project Overview
Sleep disorders significantly impact an individual's health and quality of life. This project aims to simplify the diagnosis process for medical professionals by leveraging machine learning models to predict sleep disorders with high accuracy. The study compares nine machine learning models, achieving the highest accuracy (92.42%) with the Bagging and Logistic Regression models.

Dataset
The project uses a public dataset with 12 features related to sleep habits, physical activity, and health indicators. Key preprocessing steps include:

Handling missing and duplicate values
Outlier identification and removal
Feature scaling and categorical data encoding
Oversampling to handle class imbalance (using SMOTE)
Machine Learning Models
The following models were implemented and evaluated:

Decision Tree
Random Forest
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Logistic Regression
AdaBoost
Gradient Boosting (GradBoost)
XGBoost
Bagging
Results
Model	Accuracy	Precision	Recall	F1-Score
Bagging	92.42%	0.924	0.924	0.924
Logistic Regression	92.42%	0.924	0.914	0.916
Random Forest	92.42%	0.926	0.924	0.923
Gradient Boosting	89.4%	0.893	0.894	0.893
AdaBoost	90.2%	0.904	0.902	0.901
For more details on the results and comparison with prior studies, refer to the Results and Discussion section in the documentation.

Tools and Libraries
Programming Language: Python
Libraries: Pandas, NumPy, Scikit-Learn, SciPy, Imbalanced-learn (SMOTE), Matplotlib, Seaborn
Key Features
Data Visualization: Distribution of sleep-related features and relationships using histograms and scatter plots.
Explainable AI: Model predictions interpreted using the LIME library to highlight critical features influencing decisions.
Hyperparameter Tuning: Optimized model performance through parameter tuning.
Contributors
Readuanul Farid Fahim (Team Lead) - Dataset preprocessing, Logistic Regression, Report Formatting
Md. Harun Or Rashid - Random Forest, Bagging, Introduction
Masum Musfiq - Gradient Boosting, AdaBoost, Abstract, Conclusion
Mithila Sutradhar - Dataset and Preprocessing, Decision Tree, Keywords
Nasid Ahmed Chowdhury - SVM, KNN, Results and Discussion
Future Work
Incorporating advanced datasets, including health and biometric data
Applying deep learning techniques and leveraging polysomnography recordings for improved predictions
