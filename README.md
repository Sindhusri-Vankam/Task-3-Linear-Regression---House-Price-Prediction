🏠 Housing Price Prediction using Linear Regression

This project demonstrates how to build and evaluate a Linear Regression model to predict house prices based on various features like area, number of bedrooms, presence of amenities, and more.

=====================================
Dataset
=====================================
- File: Housing.csv
- Source: Provided for internship purposes
- Contains features like:
  - area, bedrooms, bathrooms, stories
  - Categorical: mainroad, guestroom, basement, furnishingstatus, etc.
  - Target variable: price (in Indian Rupees)

=====================================
Project Workflow
=====================================
1. Import & preprocess data using pandas and one-hot encoding for categorical features.
2. Split data into training and testing sets (80/20).
3. Fit a Linear Regression model using sklearn.linear_model.
4. Evaluate the model using:
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - R² Score
5. Plot the regression line for visual understanding (area vs price).
6. Interpret feature coefficients to see how each variable impacts the price.

=====================================
Tools & Libraries Used
=====================================
- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

=====================================
Sample Output
=====================================
- MAE: ₹970,043  
- MSE: ~1.75 Trillion  
- R² Score: ~0.65  
- Positive impact features: area, airconditioning, furnishingstatus_furnished
- Negative impact features: e.g., furnishingstatus_unfurnished

=====================================
How to Run
=====================================
1. Make sure you have the required libraries installed:
   pip install pandas numpy scikit-learn matplotlib seaborn

2. Run the script:
   python housing_price_prediction.py

Note: Ensure that the Housing.csv file is in the same directory as your script, or update the path in the code.
