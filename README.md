Decision Tree Classifier – Bank Marketing Campaign Prediction
Task 03 – Data Science Internship at Prodigy InfoTech

Project Overview
In this task, I built and evaluated a Decision Tree Classifier to predict whether a customer would subscribe to a term deposit based on their demographic and campaign-related data. This project focuses on data preprocessing, model building, and interpreting feature importance to extract valuable business insights.

The model helps answer:
Which features have the most impact on predicting customer conversions?

📂 Dataset
Source: Bank Marketing Dataset – UCI Machine Learning Repository

Size: 4,521 records

Features: Includes customer demographics (age, job, marital status, balance) and marketing campaign data (contact month, duration, previous outcome, etc.)

Target Variable: Whether the client subscribed to a term deposit (yes / no)

🛠️ Tools & Libraries
Python
Pandas, NumPy – Data Handling
Matplotlib, Seaborn – Data Visualization
Scikit-learn – Model Training & Evaluation

⚙️ Workflow
Data Loading & Exploration – Checked dataset shape, columns, and target distribution.

Data Preprocessing – Handled missing values, encoded categorical features, and scaled numeric variables.

Train-Test Split – 70-30 split for training and testing.

Model Building – Implemented Decision Tree Classifier using sklearn.tree.DecisionTreeClassifier.

Model Evaluation – Calculated accuracy and plotted confusion matrix.

Feature Importance Analysis – Identified top factors influencing predictions.

📊 Key Results
Model Accuracy: 89%
Most Important Features:
duration (call length)
day (day of contact)
balance (bank account balance)
age (customer’s age)

Visualizing feature importance helps businesses prioritize high-impact variables in marketing strategies.

📈 Visuals
Top 10 Feature Importances

Decision Tree Structure

💡 Key Learnings
Learned how to preprocess categorical and numerical variables for ML models.

Understood how to interpret decision tree outputs to explain predictions.

Gained experience in visualizing and explaining feature importance for business impact.

🔗 Repository Contents
decision_tree_classifier.py – Model implementation code.

feature_importance.png – Feature importance visualization.

decision_tree_plot.png – Visualization of the trained decision tree.
