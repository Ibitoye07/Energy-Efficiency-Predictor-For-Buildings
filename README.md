# Powerminds--Data-Science
Energy Efficiency: Building a Machine Learning Model to Predict Heating and Cooling Loads of Buildings
This project builds a predictive model to predict heating and cooling loads of buildings based on the following features: Relative Compactness, Surface Area, Wall Area, Roof Area, Overall Height, Orientation, Glazing Area, Glazing Area Distribution.

⚙️ Methodology

1. **Data Preprocessing**
   - Normalization, encoding categorical features
   - Train-test split (80/20)

2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmaps
   - Pairplots and distribution plots

3. **Modeling (Multi-Target Regression)**
   - `Linear Regression`
   - `Random Forest Regressor`
   - `XGBoost Regressor`  
   Models were wrapped using `MultiOutputRegressor` to predict both heating and cooling loads simultaneously.

4. **Evaluation Metrics**
   - Mean Squared Error (MSE)
   - R² Score
