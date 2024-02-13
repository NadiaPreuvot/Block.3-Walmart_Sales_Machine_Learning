# Walmart Weekly Sales Prediction

## Overview
This project aims to build and evaluate machine learning models to predict weekly sales for Walmart stores. By leveraging economic indicators and store information, we strive to create a model that helps Walmart understand sales patterns and inform strategic marketing decisions.

## Business Context
Walmart, as a leading retail corporation, requires precise sales forecasting for effective inventory management, resource allocation, and marketing campaign planning. Accurate sales predictions enable Walmart to optimize operations and enhance customer satisfaction while reducing operational costs.

## Dataset Description
The dataset contains historical sales data for 20 Walmart stores. Each record includes weekly sales, store details, and economic indicators like unemployment rates and fuel prices.

## Project Structure
The project is structured in three main parts:
1. **Exploratory Data Analysis (EDA)**: We performed an initial analysis to understand the data, identify patterns, and prepare for modeling.
2. **Baseline Model**: We developed a baseline linear regression model to establish an initial performance benchmark.
3. **Regularized Models**: We implemented Ridge and Lasso regression to improve the model by addressing overfitting and feature selection.

## Methodology
- Preprocessing: Handled missing values, created new features from the 'Date' column, and removed outliers.
- Model Training: Trained linear regression, Ridge, and Lasso models using `GridSearchCV` to tune hyperparameters.
- Model Evaluation: Assessed model performance using R-squared on both training and test datasets.

## Key Findings
- The models indicated that store type, economic indicators, and certain times of the year significantly influence weekly sales.
- Regularization improved model generalization, with Lasso providing a slightly better R-squared score and feature selection.

## Business Impact
By implementing our model, Walmart can anticipate sales trends, better manage stock levels, and plan marketing strategies more effectively. This can lead to increased operational efficiency and higher profit margins.

## Repository Contents
- Jupyter notebooks with data analysis and modeling steps.
-  The dataset used for this project.
- README file, providing an overview of the project.

## Usage
To run the analysis and model training, follow these steps:
1. Clone the repository.
2. Install required Python packages using
   ```
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebooks.

## Future Work
- Explore more advanced modeling techniques like ensemble methods.
- Conduct a deeper feature engineering process to uncover more insights.
- Implement the model in a production environment for real-time predictions.

## Contact Information
For inquiries or further discussions about this project, please contact me at [preuvot.nadia@gmail.com].

