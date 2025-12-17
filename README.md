# Smartphone-Addiction-Analysis-Using-Machine-Learning
Machine learning–based analysis of smartphone usage behavior to predict addiction levels using behavioral and psychological indicators, with data preprocessing, EDA, visualization, and model comparison.

📌 Project Overview
Smartphone addiction has become a growing concern among youth, impacting mental health, sleep quality, and daily productivity.
This project applies data analysis, visualization, and machine learning techniques to identify patterns of smartphone usage and predict addiction levels based on behavioral indicators.

The study focuses on understanding:

Smartphone usage habits
Anxiety and sleep-related behaviors
Impact of excessive usage on daily life
Prediction of smartphone addiction using ML models

🎯 Objectives
Perform exploratory data analysis (EDA) on smartphone usage data
Preprocess and encode categorical variables
Visualize behavioral and psychological patterns
Build and compare multiple machine learning models
Predict smartphone addiction risk among users
Evaluate model performance using standard metrics

📂 Dataset Description

The dataset contains survey-based responses related to smartphone usage behavior and mental health indicators.

Features Used:
Age
Gender
Daily Usage Hours
Phone Usage Before Sleep
Anxiety Without Phone
Checks Per Hour
Impact on Daily Life
Time Without Checking Phone

Target Variable:
Self-Reported Smartphone Addiction
1 → Yes
0 → No
-1 → Not Sure


🧹 Data Preprocessing

Removed irrelevant columns
Handled missing values using mode imputation
Converted categorical responses into numerical values
Encoded behavioral intensity using ordinal mappings
Checked correlations using heatmaps
Prepared data for machine learning models

📊 Exploratory Data Analysis (EDA)
Visualizations were used to extract insights such as:
Distribution of smartphone addiction levels
Relationship between phone checking frequency and addiction
Daily usage hours vs addiction
Anxiety without phone vs addiction
Phone usage before sleep vs addiction
Correlation between behavioral factors


🤖 Machine Learning Models Used


Three classification models were implemented and compared:
k-Nearest Neighbors (KNN)
Logistic Regression
Decision Tree Classifier

Evaluation Metrics:
Confusion Matrix
Precision, Recall, F1-Score
Accuracy
Cross-validation accuracy

📈 Model Evaluation & Results
Logistic Regression showed stable and consistent performance
KNN captured behavioral similarities effectively
Decision Tree provided interpretability but was prone to overfitting
Cross-validation confirmed model robustness

🔍 Key Insights
Higher daily usage hours strongly correlate with addiction
Frequent phone checking increases addiction risk
Anxiety without phone is a strong behavioral indicator
Phone usage before sleep is associated with higher addiction levels
Smartphone addiction shows behavioral rather than demographic dominance


🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn

Jupyter Notebook

📁 Project Structure
📦 Smartphone-Addiction-Analysis
 ┣ 📜 smartphone_addiction_analysis.ipynb
 ┣ 📊 smartphone_addiction-dataset.csv
 ┣ 📄 README.md
