# Concrete Compressive Strength Predictor

Predicts the compressive strength (MPa) of concrete from its mix
ingredients and age, using the UCI Concrete Compressive Strength
dataset (1,030 samples, 8 input features).

## Models
- Linear Regression: R2 = 0.63, MAE = 7.75 MPa
- Random Forest: R2 = 0.88, MAE = 3.78 MPa

## Findings
Age, cement content, and water content are the most important
features, consistent with concrete curing behavior and the
water-cement ratio.

## Tools
Python, pandas, scikit-learn, matplotlib (Google Colab)
