Social Network Ads Prediction Project

The aim of this project was to predict whether users would purchase a product based on their age and estimated salary using the Social Network Ads Dataset. This dataset contains 400 records with features such as Age, EstimatedSalary, and a binary target variable Purchased.

Project Overview:
Data Exploration: The dataset consists of three key columns: Age, EstimatedSalary, and Purchased. After conducting an initial analysis, I confirmed that there were no missing values, making the data ready for modeling. A correlation analysis revealed that age has a significant positive relationship with the purchase likelihood.

Data Visualization: I visualized the relationship between Age and Purchased using scatterplots and regression plots. These visualizations indicated that older users were more likely to make purchases, suggesting that age is an important factor in predicting buying behavior.

Model Development: I implemented three classification models to predict purchase behavior:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
The data was divided into training (70%) and testing (30%) sets. Each model was trained on the training set and evaluated using metrics such as precision, recall, and F1-score to assess their performance.

Model Evaluation:

Logistic Regression: This model achieved an accuracy of 86% on the test set, performing well in identifying both purchasing and non-purchasing users. this model provided enhanced generalization and stability, making it the most reliable option for this dataset.
Decision Tree Classifier: It achieved an accuracy of 78%, less than  the Logistic Regression model by capturing more positive cases (buyers).
Random Forest Classifier: It achieved an accuracy of 80%, slightly improving upon the Decision Tree Classifier model by capturing more positive cases (buyers).
Conclusion:
The Logistic Regression proved to be the most effective model for predicting user purchases based on social network ads, highlighting its capacity to manage complex data relationships. This project illustrates the potential of machine learning techniques to improve marketing strategies by accurately targeting potential customers.
