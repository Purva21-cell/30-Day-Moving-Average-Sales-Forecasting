# 30-Day Moving Average Sales Forecasting

## Overview
This project implements a time-series forecasting model using the **30-day moving average method** to predict future sales based on historical sales data. It analyzes sales trends, generates forecasts, visualizes actual and predicted values, and evaluates model performance.

## Objectives
- Analyze historical sales data.
- Calculate a 30-day moving average.
- Forecast sales for the upcoming month.
- Visualize historical trends and forecast values.
- Evaluate prediction performance using Mean Absolute Error (MAE).
- Export forecast results to CSV format.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Methodology
1. Load the sales dataset.
2. Clean and preprocess the data.
3. Convert the date column to datetime format.
4. Set the date as the index.
5. Calculate the 30-day moving average.
6. Generate next-month sales forecasts.
7. Visualize actual sales and forecast results.
8. Evaluate forecast accuracy using MAE.
9. Export predictions to a CSV file.

## Model
The project uses the Moving Average forecasting technique. The forecast is calculated from the average sales values of the previous 30 days.

\[
Forecast = \frac{1}{30}\sum_{i=1}^{30} Sales_i
\]

This method provides a simple baseline for time-series forecasting and helps identify general sales trends.

## Evaluation
The model performance is evaluated using **Mean Absolute Error (MAE)**, which measures the average absolute difference between actual and predicted sales values.

Lower MAE values indicate better forecasting accuracy.

## Project Structure

```text
30-Day-Moving-Average-Sales-Forecasting/
│
├── sales_moving_average_forecast.ipynb
├── sales_forecast.csv
├── README.md
└── .gitignore
```

## Results
- Generated sales forecasts for the upcoming period.
- Visualized historical sales and predicted sales.
- Evaluated model accuracy using MAE.
- Exported forecast results for further analysis.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/30-Day-Moving-Average-Sales-Forecasting.git
   ```

2. Navigate to the project directory.

3. Install the dependencies:

   ```bash
   pip install pandas numpy matplotlib scikit-learn jupyter
   ```

4. Launch Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

5. Open `sales_moving_average_forecast.ipynb` and run all cells.

## Future Improvements
- Compare multiple forecasting techniques.
- Incorporate seasonal trends.
- Experiment with different moving-average window sizes.
- Implement exponential smoothing and other time-series models.
- Improve forecast accuracy using advanced forecasting methods.

## Author
## Purva Ghate ##
Created as a Python data analytics and time-series forecasting project.
