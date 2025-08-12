# K-Nearest Neighbors (KNN) - Iris Dataset (Task 6)

## Overview
This project implements and practices the **K-Nearest Neighbors (KNN)** classifier on the Iris dataset. The notebook includes normalization, experimentation with different k values, evaluation with accuracy and confusion matrix, and visualization of decision boundaries.

## Steps Followed
1. Load Iris dataset and encode labels.  
2. Split into train and test sets (80/20), stratified.  
3. Normalize features using `StandardScaler`.  
4. Train KNN for k = 1..15 and record train/test/CV accuracies.  
5. Select best `k` (by test accuracy), show confusion matrix and classification report.  
6. Visualize decision boundaries using two features (SepalLength vs SepalWidth).

## Results
- Best k (by test): **k = 1** (test accuracy ≈ 96.67%)  
- Confusion Matrix (example):
