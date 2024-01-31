**Paris Weather Data Analysis and Energy Consumption Correlation**

**Overview**

This project analyzes the 2017 weather data from Paris and investigates its correlation with energy consumption. The analysis includes data preprocessing, interpolation to fill missing values, correlation analysis, and linear regression modeling to predict energy consumption based on weather conditions.

**Data Preprocessing**

The dataset Paris\_weather\_data\_2017.csv is initially cleaned by removing non-numerical columns and handling missing values through linear interpolation, ensuring a consistent dataset for analysis.

**Analysis**

Correlation Analysis: A correlation matrix is constructed to identify relationships between different weather parameters and energy consumption.

Energy Consumption Prediction: Utilizing linear regression and quadratic fitting, we predict energy consumption based on mean temperature, exploring the impact of weather on energy needs.

Feature Engineering: Additional variables, such as day of the week, were engineered to enhance the model's predictive capabilities.

Overfitting Mitigation: Discussed approaches to prevent overfitting, including regularization and ensemble modeling, to improve model generalization on unseen data.

**Key Findings**

A quadratic relationship between the average temperature and daily energy consumption is identified, highlighting optimal temperatures for minimal energy usage.

Day of the week influences energy consumption, with distinct patterns observed for weekdays and weekends.

Regularization and ensemble methods are recommended for enhancing model performance and preventing overfitting.

**Technologies Used**

Python for data manipulation and analysis.

Pandas for data preprocessing.

Matplotlib and Seaborn for data visualization.

Statsmodels for regression analysis.

**Conclusions**

The analysis reveals significant correlations between weather conditions and energy consumption in Paris for the year 2017. By understanding these relationships, energy distribution can be optimized according to weather patterns, leading to more efficient energy use.