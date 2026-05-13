# Car Price Prediction

Predicting car prices using regression models based on EngineV, 
Registration, Brand and other vehicle features.

**Dataset:** [Car Sales CSV](https://www.kaggle.com/datasets/smritisingh1997/car-salescsv)  
**Type:** Regression  
**Stack:** Python · Pandas · Scikit-learn · Matplotlib  

## Approach
- Exploratory Data Analysis
- Feature Engineering
- Random Forest Regression + RandomizedSearchCV
- Model Evaluation

## Results
| Metric | Score |
|--------|-------|
| R² Score | 0.879 |
| RMSE | 7,574 |

**Best Parameters:** n_estimators=800, max_depth=30
