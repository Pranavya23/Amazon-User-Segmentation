# Amazon-User-Segmentation
Implementation of machine learning algorithms to predict the category of the customer

# Problem Statement
The goal of this project is to build a predictive model to categorize customers based on various behavioral scores. Specifically, the target column to be predicted is customer_category. This involves analyzing customer data and implementing machine learning models to accurately predict the category each customer belongs to.

# Dataset Description
The dataset consists of 10,378 samples with 10 features, including customer behavioral scores and categorical data.
The dataset consists of the following columns:
![image](https://github.com/user-attachments/assets/df954818-4f8e-4509-81d4-d41133960880)

# Machine Learning Models Implemented
Five different machine learning models were implemented to predict the customer category: Decision Tree, K-Nearest Neighbors (KNN), Naive Bayes, Logistic Regression, and Support Vector Machine (SVM). Each model was evaluated based on accuracy, precision, recall, and F1 score to determine their performance.

# Comparative Analysis of Model Performance
Decision Tree:
The Decision Tree model achieved an accuracy of 95.74%, with a precision of 95.73%, recall of 95.74%, and an F1 score of 95.74%. This model demonstrated strong performance, indicating its ability to effectively capture the structure of the data and make accurate predictions.

K-Nearest Neighbors (KNN):
The KNN model slightly outperformed the Decision Tree with an accuracy of 96.63%, precision of 96.60%, recall of 96.63%, and an F1 score of 96.47%. The improved performance of KNN suggests its effectiveness in leveraging the proximity of data points to make more accurate predictions, particularly in this customer segmentation task.

Naive Bayes:
The Naive Bayes model achieved an accuracy of 93.96%, precision of 94.34%, recall of 93.96%, and an F1 score of 94.11%. While its performance was slightly lower compared to Decision Tree and KNN, Naive Bayes remains a valuable model due to its simplicity and efficiency, particularly for large datasets.

Logistic Regression:
Logistic Regression demonstrated robust performance with an accuracy of 96.44%, precision of 96.45%, recall of 96.44%, and an F1 score of 96.23%. Its strong results highlight the model's capability to effectively handle linear relationships in the data, making it a reliable choice for classification tasks.

Support Vector Machine (SVM):
The best-performing model was SVM, which achieved an accuracy of 96.98%, precision of 96.96%, recall of 96.98%, and an F1 score of 96.85%. The superior performance of SVM underscores its effectiveness in finding the optimal hyperplane that maximizes the margin between classes, thus making highly accurate predictions.

# Conclusion
This comparative study demonstrates the application of various machine learning algorithms to predict customer categories based on behavioral scores. Each model showed distinct strengths, with SVM emerging as the most effective model for this specific task. Data visualization tools like Tableau provided valuable insights, enhancing the overall understanding of customer behavior. This comprehensive approach highlights the importance of combining data preprocessing, model training, and visualization to achieve accurate and insightful results in customer segmentation.
