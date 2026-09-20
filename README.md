# car_sales_regreesion_analysis
Car Sales Regression Analysis using Python and Machine Learning
## Introduction
This project analyzes a car sales dataset using Python, exploratory data analysis, data visualization and regression analysis.
## Problem Statement
The objective is to analyze the relationship between different car-related variables and sales and develop a regression model for prediction.
## Objectives
- Analyze car sales data
- Clean and preprocess the dataset
- Perform exploratory data analysis
- Visualize important relationships
- Perform correlation analysis
- Build a regression model
- Evaluate model performance
- Analyze actual vs predicted values
## Dataset
The dataset contains 500 records related to car sales.
## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Excel
## Project Workflow
1. Data Collection
2. Data Loading
3. Data Cleaning
4. Exploratory Data Analysis
5. Data Visualization
6. Correlation Analysis
7. Feature Selection
8. Train-Test Split
9. Regression Model
10. Model Evaluation
11. Residual Analysis
12. Conclusion

## Visualizations
The project includes:

- Distribution charts
- Correlation heatmap
- Scatter plots
- Regression plots
- Box plots
- Actual vs predicted chart
- Residual plot
- Regression coefficient chart

## Model Evaluation

The model is evaluated using:

- MAE
- MSE
- RMSE
- R² Score

## Conclusion

The project demonstrates the application of Python-based exploratory analysis and regression techniques to car sales data.
sns.heatmap(
    df.corr(numeric_only=True),
    annot=True,
    cmap="coolwarm"
)

plt.title("Correlation Heatmap")
plt.show()
