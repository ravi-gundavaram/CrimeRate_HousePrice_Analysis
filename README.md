Crime Rate vs Median Home Value Analysis
This project analyzes the relationship between the crime rate and the median home value using a given dataset. The objective is to determine how much the median home value changes (in dollars) for every 0.01 increase in the crime rate.

Objective
The goal of this analysis is to answer the following question:

"Given all things being equal, for every 0.01 increase in the crime rate, how much does the median house price go up or down in dollars?"

Dataset
The dataset contains the following columns relevant to this analysis:

crime rate: Crime rate in the area.
Median Home Value: Median home value in thousands of dollars.
Additional features like residential land zone, number of rooms, etc.
The dataset has been preprocessed to handle missing values, and columns were renamed for easier accessibility.

Steps in Analysis
1. Exploratory Data Analysis (EDA)
Visualize the Data: A scatter plot was created to show the relationship between the crime rate and Median Home Value.
Correlation Analysis: Calculated the correlation coefficient to measure the strength and direction of the relationship.
2. Linear Regression
A simple linear regression model was fitted to determine how the Median Home Value changes with crime rate.
The slope (coefficient) of the regression model was used to calculate the dollar impact for every 0.01 increase in the crime rate.
3. Model Evaluation
The R-squared value was computed to evaluate the accuracy of the model.
4. Visualization of Results
A regression line was plotted over the scatter plot to visualize the model's fit.
Findings

Correlation:

The correlation between crime rate and Median Home Value is -0.3883, indicating a [negative/positive] linear relationship.

Impact on Median Home Value:

For every 0.01 increase in the crime rate, the median home value changes by approximately -0.09 dollars.

Model Accuracy:

The R-squared value of the regression model is 0.1508, indicating that 15.08% of the variation in the median home value is explained by the crime rate.

Prerequisites

Install Python 3.10+ on your system.
Install the following Python libraries:

pip install pandas matplotlib scikit-learn

Conclusion
The analysis reveals a [negative/positive] relationship between the crime rate and the median home value. The linear regression model quantifies this relationship, showing that for every 0.01 increase in the crime rate, the median home value changes by approximately -0.09 dollars.

