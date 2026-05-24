# Weather Trend Forecasting

## Project Overview

This project analyzes global weather data to explore climate patterns, environmental relationships, and temperature forecasting using machine learning techniques.

The project includes:
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Climate and environmental analysis
- Outlier detection
- Forecasting model development
- Ensemble learning and model comparison

Machine learning models such as Linear Regression and Random Forest Regressor were implemented to predict temperature trends using weather and environmental features.

## Dataset

Dataset Source:
- Global Weather Repository (Kaggle)
- Contains over 140,000 weather observations and 40+ weather-related features from cities worldwide.

Key features include:
- Temperature
- Humidity
- Wind speed
- Precipitation
- Air quality indicators
- UV index
- Visibility
- Pressure

## Project Structure

```text
weather-trend-forecasting/
│
├── data/
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_advanced_eda.ipynb
│   ├── 03_forecasting_models.ipynb
│
├── visuals/
├── models/
├── README.md
└── requirements.txt
```

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Model Performance Summary

| Model | MAE | RMSE | R² Score |
|---|---|---|---|
| Linear Regression | 6.08 | 8.36 | 0.26 |
| Random Forest | 3.05 | 4.60 | 0.78 |
| Ensemble Model | 4.28 | 5.85 | 0.64 |

### Best Performing Model
Random Forest Regressor achieved the strongest forecasting performance with the lowest prediction error and highest robustness.

## Key Insights

- Strong geographical temperature differences were identified across countries and regions.
- Environmental variables such as PM2.5 and ozone demonstrated meaningful relationships with temperature.
- Weather data exhibited nonlinear relationships that were better captured by Random Forest models.
- Ensemble learning improved stability compared to Linear Regression alone.

## How to Run

1. Clone the repository
2. Install required libraries:

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook:

```bash
jupyter notebook
```

4. Run notebooks in sequence:
- 01_data_understanding.ipynb
- 02_advanced_eda.ipynb
- 03_forecasting_models.ipynb

## Demo Video

[Watch Demo Video](https://drive.google.com/file/d/1zCaLelOcIdS8c_Kk-r_afvzLWdNa1QNQ/view?usp=sharing)

## Future Improvements

- Implement Gradient Boosting and XGBoost models
- Develop interactive dashboards
- Apply advanced time-series forecasting methods
- Improve feature engineering techniques

