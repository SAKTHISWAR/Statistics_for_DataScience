# Statistics for Data Science
Date: 30/08/2025

This folder contains Python code that demonstrates different techniques for removing outliers from a dataset. Outlier detection is an important step in data preprocessing, as extreme values can distort statistical analysis and machine learning model performance.

# Methods used for Outlier Removal

### Normal Distribution Approach

Assumes the data follows a Gaussian (bell-shaped) distribution.
Outliers are detected based on values lying far from the mean (e.g., beyond 4 standard deviations).


### Z-Score Method

Standardizes the data by subtracting the mean and dividing by the standard deviation.
Data points with Z-score > threshold (commonly 4 or -4) are considered outliers.


### Quantile (IQR) Method

Uses the Interquartile Range (IQR) between the 25th percentile and 75th percentile.
But in this code, the outlier is being removed with the help of the percentile value which is greater than quantile(0.99). 

#### Summary

=> Normal Distribution works well for bell-shaped data.

=> Z-Score is widely used when data is approximately normal.

=> Quantile (IQR) is robust for skewed distributions and is commonly used in boxplot analysis.

These methods help in improving data quality, ensuring better statistical analysis and reliable machine learning outcomes.
