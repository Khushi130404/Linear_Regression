# Placify_LR_Model

This project predicts the placement salary (LPA) based on CGPA and IQ. The goal is to model the relationship between these features and predict LPA using three types of Linear Regression models: Single Linear Regression, Multiple Linear Regression, and Polynomial Linear Regression. Both self-created and sklearn implementations are used to compare the results of the models.

## Types of Linear Regression (LR)
1. Single Linear Regression (LR)
- This model uses only one feature (either CGPA or IQ) as the independent variable to predict the LPA.

2. Multiple Linear Regression (LR)
- This model uses both CGPA and IQ as independent variables to predict LPA, allowing for a more accurate and comprehensive prediction.

3. Polynomial Linear Regression (LR)
- This model transforms the input features into polynomial features and fits the data to capture non-linear relationships.

Both the self-created class for Linear Regression and sklearn's LinearRegression class are used to implement these models, providing a comparison between the two approaches.

## Libraries Used

- numpy - For numerical operations
- pandas - For data handling and manipulation
- matplotlib - For plotting visualizations
- sklearn - For implementing linear regression models and evaluation metrics
- seaborn (optional) - For enhanced data visualization
- math - For mathematical operations

## Visualization

- Scatter plots to show the distribution of CGPA, IQ, and LPA.
- Line plots to visualize the regression lines for each model.
- Comparison charts to evaluate and compare the results of the models.
  
The visualizations help in understanding how well each model fits the data and highlight the differences between the regression techniques.
