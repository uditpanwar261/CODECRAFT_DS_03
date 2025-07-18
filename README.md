# CODECRAFT_DS_03
Built a Decision Tree Classifier using the Bank Marketing dataset to predict whether a customer will subscribe to a term deposit. Performed data preprocessing, model training, and visualized the decision tree for interpretability.

# Bank Marketing Prediction using Decision Tree
A machine learning project using a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on their demographic and behavioral data from the UCI Bank Marketing Dataset.

# Project Overview
This project demonstrates a supervised classification task using a Decision Tree model trained on the Bank Marketing dataset. It includes data preprocessing, feature engineering, model training, evaluation, and visualization of the decision-making process.

# Dataset Details

Source: https://archive.ics.uci.edu/ml/datasets/Bank+Marketing
Samples: 45,211

Features: 16 independent variables + 1 target (y)

Target:

yes: customer subscribed

no: customer did not subscribe

# Steps Performed

🔹 Loaded and explored the dataset

🔹 Cleaned missing values using dropna()

🔹 Converted categorical variables using label encoding and one-hot encoding

🔹 Trained a DecisionTreeClassifier from scikit-learn

🔹 Visualized the decision tree using plot_tree()

🔹 Evaluated model performance using accuracy and confusion matrix

# Model Accuracy
Training Accuracy: 97.6%

Test Accuracy: 88.3% (may vary slightly depending on train-test split)

# Key Features Identified
duration was the most influential feature

Other impactful features: poutcome, previous, contact, month

# Decision Tree Visualization

The tree was plotted using Matplotlib for interpretability.
Each node shows the feature split, class distribution, and predicted outcome.

🔎 Tip: Trees can be visualized using plot_tree() with increased figure size and font for clarity.

# Technologies Used

Python 3.10

pandas

scikit-learn

matplotlib


# Future Enhancements

Prune the tree to reduce overfitting

Try ensemble models (Random Forest, XGBoost)

Create an interactive web app using Streamlit or Flask

Perform hyperparameter tuning with GridSearchCV

# License

This project is open-source and available under the MIT License.

