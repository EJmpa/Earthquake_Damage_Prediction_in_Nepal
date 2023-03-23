# Earthquake Damage in Kavrepalanchok
In to predict building damage in the Kavrepalanchok district, I developed and compared a logistic regression and decision tree model. This area is a good choice for investigating how these models can be used to forecast building damage because it has the most observations in the id map table.

# Data Splitting
I used a randomized split to divide the data into training and validation sets to make sure the models generalized well to the fresh, unexplored data. 20% of the total data made up the validation set.

# Performance Metric
Accuracy, which is the percentage of properly identified observations out of all observations, was the performance metric employed. It was decided to utilize accuracy since it is a straightforward metric that gives a good overall picture of model performance.

# Logistic Regression Model
To predict building damage, I first created a logistic regression model. Using the validation data as well as the training data, the model was assessed. The logistic regression model was not capable of predicting building damage relatively well.

# Decision Tree Model
To test how well a decision tree model would work, I also choose to try it. To train the model at all depths from 1 to 15, I developed a for loop. The best value of max depth that would give me the best validation accuracy score was then determined by plotting a validation curve.

For the test data, the decision tree model performed exceptionally well. The final decision tree model was constructed using the best max depth value. The decision tree model's accuracy score was higher than the baseline accuracy.

# Feature Importance
I took the features and their relative importance from the decision tree model and used them to explain the results. Understanding which aspects in the Kavrepalanchok district were most crucial for predicting building damage can be done by looking at their relative relevance.

I created a bar chart showing the features' Gini relevance. The Gini importance quantifies a feature's overall contribution to impurity reduction. This assisted in determining the key indicators for predicting building damage in the Kavrepalanchok neighborhood. The three most crucial characteristics were age_ building, height_ pre_ earthquake, and roof_type.