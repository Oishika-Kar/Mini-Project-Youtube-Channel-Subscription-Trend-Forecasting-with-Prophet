# Youtube-Channel-Subscription-Trend-Forecasting-with-Prophet

## Overview
This project aims to forecast subscription trends using the Prophet model, which is designed to handle time series data with complex seasonal patterns, long-term trends, and disruptions such as holidays or special events. The objective is to generate accurate and interpretable predictions for subscription data, providing insights for business strategy and decision-making.

## Why Prophet?
The Prophet model was chosen for its:
- **Ability to handle seasonal patterns**: Automatically detects weekly, yearly, and custom seasonality.
- **Robustness to missing data and outliers**: Ideal for real-world data with gaps or irregularities.
- **Flexibility**: Easily incorporates external factors such as holidays or custom seasonalities.
- **Scalability**: Efficiently works with large datasets and can model non-linear trends.

By leveraging Prophet, this project captures both regular and irregular patterns in the subscription data to ensure reliable forecasting.

## Project Structure

## Usage

1. **Data Preprocessing**: 
- Prepare your subscription data by placing it in the `data/` directory.
- The data should contain a `ds` column (date) and a `y` column (subscription count).

2. **Model Training**:
- Open the Jupyter notebooks in the `notebooks/` folder to explore the data and train the Prophet model.
- The model will predict subscription trends and provide forecasts with uncertainty intervals.

3. **Forecasting**:
- After training the model, use the `forecast.py` script in the `src/` folder to generate predictions for future subscription trends.

4. **Results**:
- The forecasted results will include trend components, seasonality, and residuals, allowing for detailed analysis of the subscription behavior.

## Dependencies

This project requires the following Python packages:
- `prophet`
- `pandas`
- `matplotlib`
- `numpy`
- `seaborn`
- `jupyter`

You can install all dependencies using: 
pip install -r requirements.txt

## Contact

For any inquiries or suggestions, feel free to reach out to oishika.kar@gmail.com.


