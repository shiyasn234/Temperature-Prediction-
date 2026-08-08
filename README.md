# Weather Temperature Prediction using Multiple Linear Regression
## Research Problem
Predicting daily average temperature (`tavg`) based on atmospheric weather parameters such as minimum temperature, maximum temperature, precipitation, wind speed, and surface pressure using Multiple Linear Regression.
## Dataset
* **Dataset File:** `weather_Rourkela_2021_2022-selected-columns.csv`
* **Features:** `tmin` (Min Temp), `tmax` (Max Temp), `prcp` (Precipitation), `wspd` (Wind Speed), `pres` (Pressure)
* **Target Variable:** `tavg` (Average Temperature in °C)
## Methodology
1. **Data Preprocessing:** Filtered missing values using `dropna()` for selected weather parameters.
2. **Train/Test Split:** Split data into training (80%) and testing (20%) sets.
3. **Model Training:** Trained a `LinearRegression` model using `scikit-learn`.
4. **Evaluation:** Evaluated performance using MAE, MSE, RMSE, and R² Score.
## Model Performance

| Metric | Description |
| :--- | :--- |
| **R² Score** | Coefficient of Determination |
| **MAE** | Mean Absolute Error |
| **RMSE** | Root Mean Squared Error |

## Visualizations
![Actual vs Predicted Temperature](plot.png)
## Repository Structure
* `weather_temperature_prediction.ipynb` — Complete Python Notebook.
* `weather_Rourkela_2021_2022-selected-columns.csv` — Weather Dataset.
* `plot.png` — Scatter plot comparing Actual vs Predicted Temperatures.
