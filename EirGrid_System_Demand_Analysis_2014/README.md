**EirGrid System Demand Analysis 2014**

**Overview**

This project involves a detailed analysis of the EirGrid system's electricity demand data for the year 2014. The objective is to understand the demand patterns, identify trends and cyclical behaviors, and assess the variability and forecasting accuracy using time-series analysis methods.

**Data Preprocessing**

Data Loading and Cleaning: The dataset is loaded into pandas dataframes.

Time Series Preparation: Conversion of date and time columns to datetime objects and setting it as the index for easier time-series manipulation.

Interpolation: Linear interpolation is used to fill missing demand values in the dataset.

**Analysis**

Time Series Visualization: A line plot is generated to visualize the energy demand throughout 2014.

Autocorrelation Analysis: Calculation of autocorrelation coefficients to understand the temporal dependencies in the demand data.

Demand Variation Analysis: Analysis of demand over the course of the year, during different months, days of the week, and hours of the day.

Statistical Testing: A two-sample independent t-test is performed to determine if there is a significant difference in demand between weekdays and weekends.

**Forecasting**

Persistence Forecasting: Implementation of persistence models for various forecast horizons and calculation of Mean Absolute Error (MAE) and Mean Absolute Percentage Error (MAPE) to evaluate the accuracy.

Forecast Error Analysis: Visualization of MAE and MAPE over different forecast horizons to assess model performance.

**Technologies Used**

Python for data manipulation and analysis.

Pandas for data preprocessing.

Matplotlib and Seaborn for data visualization.

Statsmodels for statistical analysis and autocorrelation computation.

**Key Findings**

Significant seasonal and daily patterns in electricity demand were observed.

Autocorrelation analysis revealed strong temporal dependencies in the demand data.

The persistence model provided a baseline for forecasting accuracy, with MAE and MAPE analyzed over various horizons.

**Conclusion**

This analysis provides valuable insights into the demand patterns of the EirGrid system in 2014. The findings can assist in better understanding demand fluctuations and improving forecasting models for future demand prediction.