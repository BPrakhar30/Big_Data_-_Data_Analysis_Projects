**Equity Premium Prediction Using Financial Predictors**

This project provides a comprehensive analysis and prediction model for the equity premium using various financial predictors, utilizing Python libraries such as pandas, numpy, matplotlib, and scikit-learn.

**Overview of Implementation**

**Data Preprocessing and Variable Calculation**

Data Import: The dataset 'PredictorData2021.xlsx' is imported into a pandas DataFrame. The initial sheet is selected and missing values are filled with zeros.

Variable Extraction: Extracts and calculates a set of financial variables such as 'Default Yield Spread', 'Inflation', 'Stock Variance', etc., from the imported data.

Data Structure Preparation: The Vars dictionary is created to hold the calculated variables, facilitating easy access and manipulation for analysis.

**Visualization**

Plotting Variables: Generates a grid of subplots using matplotlib, displaying the trends of the financial variables over time. This visualization aids in understanding the behavior of each variable.

**Model Building and Evaluation**

Linear Regression Model: Implements a Linear Regression model to predict the equity premium using the extracted financial variables.

Performance Metrics: Calculates performance metrics including R2, RMSE, and MAE for different time periods to evaluate the model's predictive capability.

Support Vector Regression and Gradient Boosting Models: Additionally employs Support Vector Regression (SVR) with RBF kernel and Gradient Boosting Regression to predict the equity premium, comparing their performance with the Linear Regression model.

**Results and Analysis**

Performance Comparison: The performance of the models across different time frames is summarized in a DataFrame, providing insights into the model's accuracy and reliability.

Time Period Analysis: The analysis is conducted over multiple time periods to understand the stability and consistency of the model across different market conditions.

**Conclusion**

This project demonstrates a detailed approach to predicting the equity premium using financial predictors. By employing various regression techniques and evaluating their performance, it offers valuable insights into the predictability of financial markets using historical data.