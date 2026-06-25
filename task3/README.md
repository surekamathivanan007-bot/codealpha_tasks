# Task 3 - Car Price Prediction with Machine Learning

**Internship:** CodeAlpha (Data Science / Machine Learning Track)
**Intern:** Sureka Mathivanan

## Objective
Collect car-related features (brand, horsepower, mileage, etc.) and train a regression model to predict car prices. Handle data preprocessing, feature engineering, and model evaluation.

## Methodology

1. **Data Loading & Quality Check** – verified no missing values
2. **Feature Engineering** – converted Year into Car Age relative to current year
3. **Exploratory Data Analysis** – visualized price against age, mileage, brand, fuel type, and transmission
4. **Correlation Analysis** – identified which numeric features most strongly relate to price
5. **Categorical Encoding** – label-encoded Brand, FuelType, Transmission, and Owner
6. **Model Training** – compared Linear Regression and Random Forest Regressor
7. **Model Evaluation** – R², MAE, and RMSE, plus actual-vs-predicted visualization
8. **Feature Impact Analysis** – examined regression coefficients to understand what drives price

## Key Findings
- Horsepower and engine size are the strongest positive predictors of price
- Mileage (fuel efficiency) correlates negatively with price — efficient, smaller-engine cars are cheaper
- Car age and kilometers driven both reduce price, consistent with normal depreciation
- **Linear Regression (R² ≈ 0.84) outperformed Random Forest (R² ≈ 0.63)** on this dataset — with only ~40 rows, the simpler model generalized better than the more complex one, which is a useful real-world lesson about model selection on small datasets

## Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn (Linear Regression, Random Forest Regressor)
- Jupyter Notebook

