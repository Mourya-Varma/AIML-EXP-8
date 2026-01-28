AI & ML INTERNSHIP – TASK 8
Decision Tree – Bank Marketing Subscription Prediction

Objective:
To build a Decision Tree classification model to predict whether a customer will subscribe to a bank term deposit and to understand model interpretability using decision rules.

Dataset:
Bank Marketing Dataset (UCI / Kaggle – bank.csv)

Tools Used:
- Python
- Pandas
- Scikit-learn
- Matplotlib

Steps Performed:
1. Loaded the Bank Marketing dataset.
2. Converted all categorical features into numeric values using Label Encoding.
3. Separated input features (X) and target variable (y).
4. Split the dataset into training and testing sets with a fixed random_state.
5. Trained a Decision Tree Classifier with max_depth set to avoid overfitting.
6. Predicted outcomes on both training and testing data.
7. Evaluated the model using:
   - Training Accuracy
   - Testing Accuracy
   - Classification Report
8. Visualized the Decision Tree to understand decision rules.

Model Used:
Decision Tree Classifier

Evaluation:
- Compared training and testing accuracy to detect overfitting.
- Classification report used to analyze precision, recall, and F1-score.

Files Included:
- bank.csv
- task8_decision_tree.py
- README.txt
- Decision tree visualization image

Outcome:
This task helped in understanding how Decision Trees work, how overfitting occurs, and how to interpret model decisions using tree visualization.

Final Result:
Successfully built and evaluated a Decision Tree model for bank subscription prediction with clear and interpretable decision rules.
