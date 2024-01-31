**Multidimensional Poverty Index (MPI) Analysis with Financial Indicators**

This repository explores the relationship between various financial indicators and the Multidimensional Poverty Index (MPI) using Python's data analysis and machine learning libraries.

**Overview**

The project analyzes an MPI dataset to understand the impact of financial indicators on poverty levels. It employs statistical methods and machine learning models to identify significant predictors of poverty and predict MPI values.

**Features**

**Data Preparation and Visualization**

Dataset Loading: Imports the MPI dataset from an Excel file into a pandas DataFrame for analysis.

Histograms and Scatter Plots: Utilizes seaborn and matplotlib to visualize the distribution of variables and their relationship with MPI, highlighting key trends and patterns.

**Correlation Analysis**

Logarithmic Transformation: Calculates the Pearson correlation coefficient between financial indicators and MPI, both in their original and logarithmic forms, to identify linear and non-linear relationships.

Correlation Table: Summarizes the correlation coefficients in a pandas DataFrame, providing insights into the strength and direction of associations.

**Feature Engineering**

New Variables Calculation: Introduces 'nightlight\_per\_capita' and 'population\_density' as new features, offering additional perspectives on the financial indicators' impact on MPI.

**Regression Analysis**

Backward Stepwise Regression: Implements a backward stepwise regression approach to select the most significant features, optimizing the model for predicting MPI.

Model Evaluation: Compares different regression models, including Ridge Regression and Elastic Net, using feature selection to assess their effectiveness in predicting MPI.

**Advanced Modeling**

Lasso Regression with Cross-Validation: Applies Lasso regression with cross-validation to predict MPI values, evaluating model performance through correlation and R-squared metrics.

**Results**

The analysis identifies key financial indicators that significantly impact MPI, with models demonstrating varying degrees of predictive power. The project showcases the potential of statistical modeling and machine learning in poverty research.

**Conclusion**

This project highlights the importance of leveraging financial indicators to understand and predict poverty levels, providing valuable insights for policymakers and researchers aiming to address multidimensional poverty.