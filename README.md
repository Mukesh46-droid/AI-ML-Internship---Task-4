# Task 4: Classification with Logistic Regression

This project is a submission for Task 4 of the Elevate AI & ML Internship. The objective is to build, evaluate, and understand a binary classifier using Logistic Regression.

## Objective
The main goal is to predict whether a breast cancer tumor is malignant or benign based on several diagnostic features, using a logistic regression model.

## Dataset
The project uses the **Breast Cancer Wisconsin (Diagnostic) Dataset**, which is available through the `scikit-learn` library.
- **Features**: 30 numeric features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.
- **Target**: Diagnosis (Malignant = 0, Benign = 1).

## Tools and Libraries
- **Python**
- **Pandas**: For data manipulation.
- **Scikit-learn**: For model building, feature scaling, and evaluation.
- **Matplotlib**: For plotting the ROC curve.

## Methodology
The project follows these steps:
1.  **Load Data**: The dataset is loaded directly from `sklearn.datasets`.
2.  **Train-Test Split**: The data is split into 80% for training and 20% for testing.
3.  **Feature Scaling**: `StandardScaler` is used to standardize the features to ensure that all features contribute equally to the model's performance.
4.  **Model Training**: A `LogisticRegression` model is trained on the scaled training data.
5.  **Evaluation**: The model's performance is evaluated on the test set using the following metrics:
    - Confusion Matrix
    - Precision and Recall
    - ROC-AUC Score
6.  **Threshold Tuning**: The impact of changing the classification threshold on precision and recall is demonstrated.

## Results
The trained logistic regression model achieved the following performance on the test set:
- **Precision**: [Add your precision score here]
- **Recall**: [Add your recall score here]
- **ROC-AUC Score**: [Add your ROC-AUC score here]

The ROC curve plot visually confirms the model's high predictive power.

## How to Run
1.  Clone the repository.
2.  Ensure you have Python and the required libraries (`pandas`, `scikit-learn`, `matplotlib`) installed.
3.  Run the Python script `logistic_regression_classifier.py` to see the output and the ROC curve plot.
```
