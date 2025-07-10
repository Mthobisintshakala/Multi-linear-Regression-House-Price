# House Price Prediction using Multiple Linear Regression

This project aims to predict house prices using a **Multiple Linear Regression** model. The model was trained using the following features:

- **Location**
- **Size_sqft** (Size in square feet)
- **Num_Bedrooms** (Number of bedrooms)
- **Num_Bathrooms** (Number of bathrooms)
- **Has_Garage** (Garage availability)

## Model Results

The graph below compares the actual house prices in the testing set with the prices predicted by the model:

![Original vs Predicted House Prices](./Screenshot%20(10).png)

### Key Observations:

- The **predicted values** are narrowly distributed and deviate significantly from the actual values.
- The **R² score is negative**, which indicates that the model does not explain the variance in house prices and performs worse than a naive mean-based prediction.
- The model **fails to generalize** and accurately predict the testing data.

## Conclusion

Based on the analysis, the current model is not suitable for accurately predicting house prices using the existing dataset and features.

## Recommendations for Improvement

To enhance model accuracy and predictive power, the following steps are recommended:

- **Include additional relevant features** such as:
  - Year the house was built
  - Property type
  - Distance to key locations (e.g., schools, city center)
- **use a larger dataset** to improve generalization.




