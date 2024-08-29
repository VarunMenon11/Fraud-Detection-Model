# Fraud-Detection-Model

# Overview
This project was developed as part of a collaboration with TransUnion. The primary goal was to design and evaluate a fraud detection system for credit card transactions. We implemented and compared several machine learning models to identify fraudulent activities, aiming to achieve the highest possible accuracy.
This project was completed by a three-member team:
  I(Varun Menon)
  @Rajatgdev
  @NethreNair

  
# Models and Accuracy
We tested the following machine learning models on our dataset:

RandomForest: 98.6%
Support Vector Machine (SVM): 94.5%
CatBoost: 96%
K-Nearest Neighbors (KNN): 92%

# Algorithms Used
1. RandomForest
RandomForest is an ensemble learning method that builds multiple decision trees and merges them to get a more accurate and stable prediction. It works well with large datasets and can handle the problem of overfitting, making it highly suitable for fraud detection tasks.

2. Support Vector Machine (SVM)
SVM is a powerful classification algorithm that works by finding the hyperplane that best divides a dataset into classes. It is particularly effective in high-dimensional spaces and can be used for both linear and non-linear classification problems.

3. CatBoost
CatBoost is a gradient boosting algorithm that handles categorical features automatically. It is known for its high performance and speed, making it a strong candidate for complex tasks like fraud detection.

4. K-Nearest Neighbors (KNN)
KNN is a simple, non-parametric algorithm that classifies data points based on the majority class among the nearest neighbors. While it is easy to implement and understand, it may not perform as well on large datasets due to its high computational cost.

# Usage
After installing the required packages, you can run the models and generate predictions using the provided scripts. The evaluation results will be saved in the results/ directory.

bash
Copy code
python scripts/train_model.py --model randomforest

# Conclusion
Our analysis shows that the RandomForest algorithm outperformed the other models with an accuracy of 98.6%, making it the best choice for detecting fraud in credit card transactions in this project.
