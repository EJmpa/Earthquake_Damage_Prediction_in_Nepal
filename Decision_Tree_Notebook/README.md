# Predicting Earthquake Damage with Decision Tree

Building a classification model using the Decision Tree method is the goal of this project. A supervised machine learning approach called a decision tree is utilized for classification and regression problems. It divides the data according to a set of criteria (features) that best divides the data into its corresponding classes or categories.


# Data Splitting

Training, testing, and validation datasets were created from the data. During hyperparameter tuning, the model's performance was assessed using the validation dataset.

# Performance Metric

Accuracy was the performance metric  used for this model. The percentage of correctly categorized samples among all samples is how accuracy is calculated.

# Model Building

Categorical variables were encoded using the OrdinalEncoder. A scikit-learn encoder called OrdinalEncoder turns category variables into integers.

To identify the appropriate depth to train the data with and to make sure the model generalizes well to new data, some hyperparameter tuning was done because the model originally overfit the training data.

# Decision Logic Visualization

To better comprehend how the model determines its predictions, the decision logic was shown with a visualization.

# Feature Importance

To illustrate the significance of each feature in the model, a horizontal bar chart of the features and their gini relevance was made. Gini significance quantifies the contribution of each feature to the decision tree's overall impurity reduction.

Creating a classification model using the decision tree method was the final step in this process. Datasets for training, testing, and validation were created after the data had been cleansed. The model was adjusted to make sure it generalizes well to new data, and to explain the model's behavior, a visualization of the decision logic and feature importance was made.