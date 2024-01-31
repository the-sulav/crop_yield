# Crop Yield Prediction

This project aims to predict crop yields using various features such as state, district, season, crop type, crop year, production, and area. The dataset used for this analysis is the "Crop Production Statistics" dataset.

## Dataset
The dataset (`Crop_Production_Statistics.csv`) contains information about crop production statistics, including the state, district, crop details, crop year, season, area, production, and yield.

## Data Preprocessing

### Missing Value Handling
1. Removed rows with missing values in the "Production" column.
2. Removed rows with missing values in the "Crop" column.

### Data Exploration
- Explored unique values in each feature column.
- Checked for missing values in each column after preprocessing.

### Data Visualization
- Created scatter plots to visualize the relationship between crop yield and production.

### Label Encoding
- Applied label encoding

## Polynomial Regression

### Without Gradient Descent
- Explored polynomial regression for predicting crop yield.
- Utilized the `PolynomialFeatures` from scikit-learn.
- Visualized the relationship between the original and transformed features.

## Using Multiple Linear Regression
- Applied multiple linear regression to predict crop yield.
- Investigated the correlation between each feature and crop yield.
- Evaluated the model using mean squared error and R-squared.

## Omitting Features with Low Correlation
- Attempted to improve model performance by omitting features with low correlation.

## Trying All Possible Combinations
- Generated all possible combinations of features and evaluated their performance using linear regression.

## Trying Stochastic Gradient Descent (SGD)
- Explored the use of SGDRegressor for crop yield prediction.
- Applied feature scaling and partial fitting during training.

## Conclusion
The project covers various approaches to predicting crop yield, from polynomial regression to linear regression and stochastic gradient descent.

## License

This project is licensed under the [MIT License](LICENSE) - see the [LICENSE](LICENSE) file for details.
