Sales Forecasting:
- The project successfully integrated multiple datasets (restaurants, items, and sales) into a unified analytical framework, enabling comprehensive analysis at store, item, and time levels.

- Exploratory Data Analysis revealed strong temporal patterns in sales, with significant variations across weekdays, months, and quarters, highlighting the importance of seasonality in demand behavior.

- Hypothesis testing provided statistical validation for business assumptions:

    1. Sales vary significantly across weekdays and months.
    
    2. Weekend sales are not necessarily higher than weekday sales.
    
    3. Revenue is almost perfectly correlated with sales volume.
    
    4. Price has a statistically significant but practically weak impact on demand.

- Store-level and item-level analysis showed clear heterogeneity in performance, with Bob’s Diner dominating in volume and revenue, while other restaurants followed distinct pricing and positioning strategies.

- Pricing analysis using calorie efficiency identified underpriced and overpriced items, revealing a dual strategy where:

- Premium entrée items drive per-unit profit.

- Beverages and desserts act as high-volume, value-driven products.

- Machine learning models were developed and compared using a time-aware train–test split, ensuring realistic evaluation without data leakage.

- Among all models, XGBoost outperformed Linear Regression and Random Forest, achieving the lowest error metrics and highest explanatory power.

- Hyperparameter tuning further refined the XGBoost model, resulting in improved stability and generalization, confirming its suitability for production use.

- The final one-year forecast generated using the tuned XGBoost model exhibited stable, seasonally consistent trends and aligned well with historical moving averages.

- With an overall forecasting error of approximately 8% (MAPE) and high R² (~95.5%), the predictions are reliable for operational and strategic decision-making.

- The project demonstrates that advanced machine learning approaches, when combined with robust EDA and statistical validation, provide significant value over traditional methods for demand forecasting.

- The project’s insights enable data-driven optimization of inventory, staffing, pricing, and menu strategy, while the accurate one-year demand forecast supports confident operational and strategic business planning.
