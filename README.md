##  Rossmann Store Sales Forecasting

```markdown
# Rossmann Store Sales Forecasting

### Overview
Predicting daily retail store sales to improve workforce planning, inventory, and operational budgeting.

### Business Problem
Poor demand forecasting contributes to profit loss and operational inefficiencies.

### Data
- Kaggle — Rossmann Store Sales
- Time series with promotions, holidays, and store metadata

### Methods
- Feature engineering: promo flags, lagged trends, store metadata joins
- RF and Gradient Boosting models with cross-validation
- Metrics: RMSE, MAPE

### Results
- Best model reduced error by ~20% over baseline
- Promotions, store type, and competitor distance were key drivers

### How to Run
```bash
python train_model.py
