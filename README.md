# YouTube Video Metrics & Engagement Analytics

## Project Overview
This project leverages machine learning to uncover key drivers of performance and engagement across YouTube videos. The analysis explores data trends through two distinct operational lenses:
1. **Engagement Status (Classification):** Predicting whether a video will have its comment section disabled.
2. **Performance Forecasting (Regression):** Modeling and predicting continuous video view counts based on historical engagement patterns.

## Tech Stack & Advanced Methodologies
* **Language & Environment:** Python, Jupyter Notebook (Google Colab)
* **Data Manipulation & Viz:** Pandas, NumPy, Seaborn, Matplotlib, Plotly
* **Machine Learning Framework:** Scikit-Learn
* **Feature Engineering:** Preprocessing pipelines utilizing `ColumnTransformer`, `StandardScaler` for numeric scaling, `OneHotEncoder` for handling categorical data, and log transformations (`np.log1p`) to handle skewed metric distributions.
* **Optimization:** Hyperparameter tuning via `GridSearchCV` with 5-Fold Cross-Validation.

## Models Implemented
* **Classification and Regression Trees (CART):** Implemented `DecisionTreeClassifier` to analyze comment constraints and `DecisionTreeRegressor` to extract non-linear patterns behind video viewership.
* **Parametric Regression:** Deployed `Multiple Linear Regression` to establish baseline trend interpretations.
* **Regularized Modeling:** Leveraged `Ridge` and `Lasso` regression architectures to penalize coefficients, prevent overfitting, and handle potential multicollinearity between likes, dislikes, and comment numbers.

## Key Insights & Evaluation Metrics
* Extracted and visualized target feature coefficients to identify which variables most strongly influence video reach.
* Compared baseline linear models against tree-based approaches using **R² Scores**, **Mean Absolute Error (MAE)**, and **Root Mean Squared Error (RMSE)** to select the most robust predictive asset.
