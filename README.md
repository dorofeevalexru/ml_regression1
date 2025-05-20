# ml_regression1
LABORATORY WORK №1
Data Analysis Based on Regression Models

A labeled multidimensional dataset is provided. It is necessary to perform data analysis based on regression models following the sequence of steps below.

Steps:
Load the necessary packages and libraries.

Load the data from the specified source.

Perform exploratory data analysis (EDA) according to the steps described in the file *"Stages of a Machine Learning Project in Examples 1/2.pdf"*:
a. Familiarize yourself with the data using descriptive statistics methods.
b. Perform univariate data visualization to understand data distribution and multivariate visualization to identify dependencies between features.
c. If necessary, clean the data using one of the methods.
d. If required, transform textual or categorical features using one of the methods.
e. Analyze the correlation between features.
f. Experiment with attribute combinations. If necessary, add new attributes to the dataset.
g. Select significant features. Form a dataset consisting of significant features and user-added attributes.
h. Scale the data for both datasets (original and constructed) using one of the specified methods (as per the variant).

Perform the analysis for:

The original dataset (after cleaning, if necessary, and transformation of textual/categorical features using one of the considered methods).

The scaled original dataset (step 3.h).

The constructed dataset (after removing non-informative features and adding custom attributes).

The scaled constructed dataset.
For all datasets, split the data into training and test sets.

Compare linear (as per the variant) and polynomial regression models on the training and test sets for all datasets, including their scaled versions.
Use the following evaluation metrics:

Root Mean Squared Error (RMSE)

R² (Coefficient of Determination)

Draw conclusions based on the conducted analysis.

Variant:
Dataset: Startup profits depending on three types of expenses.
Build a regression model for the target feature "Profit" (startup profit) based on the other input features.

a. Step 3.h – Normalization
b. Step 4 – Ridge Regression (Regularized Linear Regression)
