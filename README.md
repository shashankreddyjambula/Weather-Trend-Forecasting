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

| Model | MAE | RMSE | R² Score |
|---------|---------|---------|---------|
| Linear Regression | 5.31 | 6.54 | 0.43 |
| Random Forest | 4.11 | 5.35 | 0.62 |
| Gradient Boosting | 4.35 | 5.64 | 0.58 |
| Ensemble Model | 4.44 | 5.60 | 0.58 |

Random Forest achieved the best overall performance with the lowest RMSE of 5.35 and the highest R² Score of 0.62. The Ensemble Model also produced competitive results, but Random Forest remained the strongest model for temperature forecasting in this project.

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


