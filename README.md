# Nepal Earthquake Building Damage Prediction

This project creates a model to forecast building damage from the Nepal 2015 Earthquake using data from Open Data Nepal. The objective is to develop a model that, given a building's attributes, can accurately predict whether or not the structure will sustain significant damage in an earthquake of a similar magnitude.

# Data

The data used in this study are made available via [Open Data Nepal](https://opendatanepal.com/). A SQLite database is used to store the data.

The data dictionary for each table is located in the "data" folder.

# Methodology

It is the objective of this classification task to predict a categorical outcome variable from a set of input features. The building's degree of damage as a result of the 2015 earthquake in Nepal is the outcome variable in this scenario, and it can either be severely damaged or not severely damaged.

Two algorithms—decision tree and logistic regression—were applied to develop a model that can predict the extent of building damage. These methods are well-liked and frequently employed for classification tasks.

Accuracy, which measures the proportion of accurate predictions made by the model, was the performance metric used to assess the models.

In order to further explore and clean the data for this project, it was first wrangled using SQL and then turned to a dataframe. In order to prepare the data for analysis, the wrangling process comprised choosing and connecting the pertinent tables from the SQLite database as well as cleaning and converting the data.

As part of this project, four Jupyter notebooks have been uploaded:

**Data Wrangling Notebook:** The SQL code used to extract the data from the SQLite database is included in this notebook, as well as the Python code used to turn the data into a dataframe and conduct preliminary exploratory analysis.

**Logistic Regression Notebook:** The Python code for developing and testing a logistic regression model for predicting building damage is contained in this notebook.

**Decision Tree Notebook:** The Python code for a decision tree model for predicting building damage is contained in this notebook.

**Model Relation Notebook:** This notebook contains the Python code used to assess how well the decision tree and logistic regression models performed in terms of making predictions for the given job.

# Utilization

You can use the included Jupyter notebooks to use the models. The steps followed and the code used are thoroughly explained in the notebooks.

