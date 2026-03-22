Decision Tree Classifier and Regressor with Pruning
Project Overview

This project implements Decision Tree Classifier and Decision Tree Regressor models using pruning techniques to improve model performance and control overfitting. The models are built using Python machine learning libraries and applied to a dataset related to user behavior in an e-commerce environment.

The primary objective is to understand how pruning parameters affect model complexity and performance.

Models Implemented
Decision Tree Classifier
Used for classification tasks
Predicts categorical outcomes (e.g., purchase or not)
Decision Tree Regressor
Used for regression tasks
Predicts continuous numerical values
Pruning Technique Used

Pruning is applied to reduce overfitting and improve generalization of the decision tree models.

The following pruning parameters were used:

max_depth
Limits the maximum depth of the tree
Controls model complexity
min_samples_split
Minimum number of samples required to split an internal node
Prevents unnecessary splits

Example:

DecisionTreeClassifier(
    max_depth=5,
    min_samples_split=10,
    random_state=42
)
Technologies and Libraries Used
Python
NumPy
Pandas
Matplotlib
Scikit-learn
Dataset

The dataset contains information about user sessions and browsing behavior in an e-commerce platform. Features include page visits, session duration, browser information, and visitor type.

Target variable:

Revenue
Indicates whether the visitor made a purchase
Workflow

The following steps were performed:

Data Loading
Data Preprocessing
Exploratory Data Analysis (EDA)
Feature Selection
Model Training
Model Evaluation
Model Pruning
Visualization of Results
Evaluation Metrics
For Classification
Accuracy
Precision
Recall
F1 Score
Confusion Matrix
For Regression
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score
Project Structure
Decision-Tree-Project/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── Decision Tree.ipynb
│
├── models/
│   ├── decision_tree_classifier.py
│   └── decision_tree_regressor.py
│
├── images/
│   └── plots.png
│
├── README.md
│
└── requirements.txt
Results
Pruning reduced overfitting
Controlled tree depth improved generalization
Model performance improved after tuning pruning parameters
