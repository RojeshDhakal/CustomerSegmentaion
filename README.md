# Marketing Campaign Analysis Project

## Overview
This project analyzes a marketing campaign dataset to understand customer behavior based on demographic and spending patterns.

## Dataset
- **Source**: [Marketing Campaign Dataset] KAGGLE.COM
- **Features**: Includes demographic information (education, marital status, income) and spending behavior (on various products).

## Steps and Analysis
1. **Data Cleaning and Preprocessing**:
   - Handled missing values in the 'Income' column.
   - Transformed categorical variables ('Education', 'Marital_Status') for better analysis.

2. **Exploratory Data Analysis**:
   - Visualized total spending against income based on education status.
   - Examined spending patterns based on marital status.

3. **Feature Scaling**:
   - Applied StandardScaler to normalize numerical data.

4. **Dimensionality Reduction**:
   - Used PCA to reduce dimensions for clustering.

5. **Clustering**:
   - Implemented K-means clustering to segment customers based on spending and demographic attributes.

## Results
- Identified clusters of customers with similar spending behaviors and demographic profiles.
- Visualized clusters using scatter plots and analyzed differences between groups.

## Visualizations
- `Education-Income.png`: Scatter plot showing spending vs. income based on education status.
- `Marital-Spending.png`: Scatter plot showing spending vs. income based on marital status.
- Many More in the Notebook.

## Future Work
- Further refinement of clustering techniques.
- Integration with predictive models for customer behavior forecasting.


