# Credit Card Fraud Detection Project

## Overview

This project aims to detect fraudulent credit card transactions using machine learning models. The primary goal is to compare the effectiveness of different models in accurately identifying fraud.

## Aim

- Develop a robust model for fraud detection.
- Train and evaluate multiple machine learning models.
- Select the best model based on evaluation metrics.

## Structure

1. **Data Preprocessing**: Loading, cleaning, and scaling data.
2. **Model Training**: Implementing KNN, Neural Network, and K-Means models.
3. **Evaluation**: Using precision, recall, and F1-score for comparison.
4. **Visualization**: PCA for data distribution and model performance visualization.
5. **Conclusion**: Summarizing and recommending the best model.

## Data set

The dataset includes credit card transactions from September 2013 by European cardholders, spanning two days with 492 frauds out of 284,807 transactions (0.172% fraud rate). All input variables are numerical and derived from a PCA transformation, except 'Time' and 'Amount'. 'Time' is the seconds elapsed since the first transaction, 'Amount' is the transaction amount, and 'Class' indicates fraud (1) or not (0).

Due to class imbalance, accuracy should be measured using the Area Under the Precision-Recall Curve (AUPRC) rather than confusion matrix accuracy.

For more resources, check the transaction data simulator from the practical handbook on Machine Learning for Credit Card Fraud Detection https://fraud-detection-handbook.github.io/fraud-detection-handbook/Chapter_3_GettingStarted/SimulatedDataset.html


## Methodology

1. **Data Handling**: Loaded, cleaned, and scaled data; addressed imbalances.
2. **Model Implementation**: Trained KNN, Neural Network, and K-Means models.
3. **Evaluation**: Compared models using precision, recall, and F1-score; used PCA for visualization.
4. **Results**: Neural Network outperformed others with an F1-score and recall of 0.964.

## Conclusion

The **Neural Network** model is the best performer for credit card fraud detection, achieving the highest F1-score and recall, making it the most reliable.

## Future Work

- Experiment with more algorithms.
- Fine-tune model hyperparameters.
- Explore advanced techniques for data imbalance.
- Implement real-time detection systems.
