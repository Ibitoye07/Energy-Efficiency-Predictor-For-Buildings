# Background
As cities grow and environmental concerns intensify, the construction industry faces mounting pressure to design greener, more energy-efficient buildings. But how do architectural choices like a building’s shape, surface area, orientation, and glazing actually impact energy usage? In this project, I explore a data-driven approach to predicting building energy efficiency, using building data and modern machine learning techniques.

# Problem Statement
Buildings in temperate regions require artificial heating (in winter) and cooling (in summer). Buildings in the tropics and monsoon climes also require cooling systems due to burning hot seasons. According to Australian Government’s Department of Climate Change, Energy, the Environment and Water, heating and cooling of buildings account for between 20% to 50% of total energy consumption depending on the climate. This necessitates the need to design architectural features to reduce heating and cooling loads of buildings. The goal is to build regression models that predict two key metrics:

● Heating Load (energy needed for heating)

● Cooling Load (energy needed for cooling)

These predictions will be based on architectural features, helping architects and engineers make informed decisions early in the design process.

# Data Preprocessing
## The Dataset

Public dataset with 768 samples and 8 architectural features

# Building Regression Models
We compare three models:

● Linear Regression

● Random Forest Regressor

● XGBoost Regressor

Models were wrapped using `MultiOutputRegressor` to predict both heating and cooling loads simultaneously.

# Model Evaluation

● R² Score

● Mean Square Error (MSE)


Random Forest and XGBoost models significantly outperform Linear Regression, achieving near-perfect predictions for both targets.

# Insights and Takeaways
● Model Choice Matters: Advanced models like Random Forest and XGBoost provide much better predictions than simple linear regression for this dataset.

● Key Features: Relative Compactness and Surface Area are critical in determining a building’s energy efficiency.

● Practical Use: These models can help architects quickly estimate energy needs and optimize designs for sustainability.

#  Conclusion
By leveraging data science, we can demystify the impact of design choices on building energy efficiency. With the right models and data, architects and engineers can make smarter, greener decisions one building at a time.
