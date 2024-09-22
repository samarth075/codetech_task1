# Predicting Housing Prices Using Linear Regression on the Ames Housing Dataset

## Objective:
To build a predictive model using linear regression to estimate housing prices based on various features from the Ames Housing dataset.

## Key Activities:
- **Data Collection**: Loaded the Ames Housing dataset using `fetch_openml` from `sklearn.datasets`.
- **Feature Selection**: Selected relevant features such as `GrLivArea`, `BedroomAbvGr`, and `Neighborhood`.
- **Data Preprocessing**:
  - Generated a correlation heatmap.
  - Converted categorical variables into numerical values using one-hot encoding.
  - Split the dataset into training and testing sets.
  - Standardized the numerical features using `StandardScaler`.
- **Model Training**: Trained a linear regression model using `LinearRegression` from `sklearn.linear_model`.
- **Model Evaluation**: Evaluated performance using MSE and R² score.

## Technology Used:
- Python
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn

## Dataset:
- Ames Housing Dataset: Loaded from `fetch_openml` via `sklearn.datasets`.
- Key Features: `GrLivArea`, `BedroomAbvGr`, `Neighborhood`.

## Conclusion:
Developed a linear regression model that predicts house prices using key features from the dataset. The model demonstrated reasonable accuracy in predicting house prices.
