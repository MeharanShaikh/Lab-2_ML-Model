# Lab-2_ML-Model
# Breast Cancer Classification

This project uses machine learning to classify breast cancer tumors as either malignant or benign. The dataset used is the Wisconsin Diagnostic Breast Cancer (WDBC) dataset, which has features calculated from images of fine needle aspirate (FNA) of breast mass.

## Dataset

The dataset has 569 instances with 32 features, including an ID number, diagnosis (M = malignant, B = benign), and 30 features from images of cell nuclei.

## Methodology

We use two machine-learning models:

1. Logistic Regression
2. Random Forest

### Steps:

1. **Data Preprocessing**:
    - Convert diagnosis labels to binary values (M = 1, B = 0).
    - Remove the ID column.
    - Standardize the features using `StandardScaler` from scikit-learn.

2. **Data Splitting**:
    - Split the data into 80% training and 20% testing sets.

3. **Model Training**:
    - Train the Logistic Regression model on the training data.
    - Train the Random Forest model on the training data.

4. **Model Evaluation**:
    - Test both models on the testing data.
    - Evaluate the models using accuracy, confusion matrix, and classification report.

## Results

The performance of the models is assessed using:
- Accuracy
- Confusion Matrix
- Classification Report

## Conclusion

This project demonstrates the use of Logistic Regression and Random Forest models to classify breast cancer tumors. The models were trained and evaluated on the WDBC dataset with satisfactory results.
