# task-4
# Logistic Regression Binary Classification

## Project Overview
This project demonstrates **Logistic Regression** for binary classification using Python's `scikit-learn`.  
We go through **data preparation, training, evaluation, and threshold tuning** 

---

## Steps Covered

1. **Choose Dataset**  
   We load a binary classification dataset (`data.csv`).

2. **Train/Test Split & Standardization**  
   - 80% of data is used for training, 20% for testing.
   - Features are standardized so they have mean 0 and variance 1.

3. **Logistic Regression Model**  
   - Fits the model to predict probabilities between 0 and 1 using the **sigmoid function**.

4. **Evaluation Metrics**
   - **Confusion Matrix**: Shows counts of TP, FP, FN, TN.
   - **Precision**: Out of predicted positives, how many were correct.
   - **Recall**: Out of actual positives, how many were found.
   - **ROC-AUC**: Measures model's overall ability to separate classes.

5. **Threshold Tuning**
   - Default threshold is 0.5.
   - Lower/higher thresholds can make the model more sensitive or specific.

6. **Sigmoid Function**
   - Formula: `1 / (1 + e^(-z))`
   - Converts raw model scores into probabilities.
