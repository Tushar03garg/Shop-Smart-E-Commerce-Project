Decision Tree Pruning System
📌 Project Overview

This project demonstrates the implementation of Decision Tree Classifier and Decision Tree Regressor models using pruning techniques to improve model performance and prevent overfitting. Decision Trees can grow very complex and memorize training data, so pruning parameters were applied to control tree size and enhance generalization.

The models were developed using Python machine learning libraries and evaluated using standard performance metrics.

🎯 Problem Statement

Decision Trees often suffer from:

Overfitting on training data
High model complexity
Poor generalization on unseen data

This project applies tree pruning techniques to:

Reduce overfitting
Improve model performance
Control model complexity
Enhance prediction accuracy
📊 Dataset Description

The dataset contains multiple input features used to train and evaluate the Decision Tree models.

Each row represents a data instance with numerical and categorical attributes.

Typical steps performed:

Data preprocessing
Feature selection
Model training
Model evaluation

Target Variable:

For Classifier → Categorical output
For Regressor → Continuous numerical output
⚙️ Technologies Used

Python 🐍
NumPy
Pandas
Matplotlib
Scikit-learn

🔄 Workflow

Data Loading
Data Cleaning
Exploratory Data Analysis (EDA)
Feature Preprocessing
Train-Test Split
Model Training
Model Pruning
Model Evaluation
Performance Comparison

🤖 Models Used

The following machine learning models were implemented:

Decision Tree Classifier
Decision Tree Regressor

🌳 Pruning Techniques Used

The following pruning parameters were applied to control tree growth:

max_depth

Limits the maximum depth of the tree
Prevents the model from becoming too complex

min_samples_split

Minimum number of samples required to split a node
Reduces unnecessary splits

Example:

DecisionTreeClassifier(
    max_depth=5,
    min_samples_split=10,
    random_state=42
)
📈 Results

Applying pruning improved model performance by:

Reducing overfitting
Controlling tree complexity
Improving prediction stability
Enhancing generalization on test data
📊 Evaluation Metrics
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

🚀 How to Run

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git

Navigate to project folder:

cd your-repo-name

Install dependencies:

pip install numpy pandas matplotlib scikit-learn

Run the notebook or script.

📁 Project Structure
├── data/
├── notebooks/
├── models/
├── README.md
└── requirements.txt
