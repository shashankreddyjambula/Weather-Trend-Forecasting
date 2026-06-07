# Weather Trend Forecasting

## Project Overview

This project analyzes the Global Weather Repository dataset to understand global weather patterns and forecast future temperature trends using machine learning techniques.

The project includes data cleaning, exploratory data analysis (EDA), anomaly detection, climate analysis, environmental impact analysis, feature importance analysis, spatial analysis, geographical pattern analysis, and forecasting using multiple machine learning models.

## PM Accelerator Mission

By making industry-leading tools and education available to individuals from all backgrounds, we level the playing field for future PM leaders. This is the PM Accelerator motto, as we grant aspiring and experienced PMs what they need most – Access. We introduce you to industry leaders, surround you with the right PM ecosystem, and discover the new world of AI product management skills.

## Dataset

Dataset: Global Weather Repository

Source: Kaggle

https://www.kaggle.com/datasets/nelgiriyewithana/global-weather-repository/code

## Methodology

### Data Cleaning and Preprocessing

* Removed duplicate records
* Handled missing values
* Treated outliers using the IQR method
* Converted the `last_updated` column into datetime format
* Created time-based features such as year, month, day, and day of year

### Exploratory Data Analysis

* Temperature Distribution Analysis
* Precipitation Distribution Analysis
* Correlation Analysis
* Temperature Trend Analysis
* Precipitation Trend Analysis

### Advanced Analysis

* Anomaly Detection using Isolation Forest
* Climate Analysis
* Environmental Impact Analysis
* Feature Importance Analysis
* Spatial Analysis
* Geographical Pattern Analysis

### Forecasting Models

* Linear Regression
* Random Forest Regressor
* Gradient Boosting Regressor
* Ensemble Model

## Results

| Model             | MAE  | RMSE | R² Score |
| ----------------- | ---- | ---- | -------- |
| Linear Regression | 4.69 | 5.61 | 0.47     |
| Random Forest     | 3.93 | 5.00 | 0.58     |
| Gradient Boosting | 4.13 | 5.21 | 0.54     |
| Ensemble Model    | 4.08 | 4.97 | 0.585    |

The Ensemble Model achieved the best overall performance with the lowest RMSE and highest R² Score.

## Key Findings

* UV Index was the most important feature for temperature prediction.
* Countries in desert regions recorded the highest temperatures and lowest precipitation levels.
* Air quality indicators showed relationships with weather variables.
* Spatial analysis revealed clear geographical temperature patterns.
* The Ensemble Model provided the most reliable forecasting performance.

## How to Run

1. Open the notebook in Google Colab.
2. Upload the Global Weather Repository dataset.
3. Install any required libraries if needed.
4. Run all notebook cells sequentially.
5. Review the generated visualizations and forecasting results.

## Repository Contents

* Weather_Trend_Forecasting.ipynb
* Weather_Trend_Forecasting_Report.pdf
* README.md
* requirements.txt

## Conclusion

This project successfully analyzed global weather patterns and developed machine learning models to forecast future temperature trends. The results demonstrate how data science techniques can be applied to understand weather behavior and improve forecasting accuracy.


