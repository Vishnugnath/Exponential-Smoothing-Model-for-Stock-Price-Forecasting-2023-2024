
# Exponential Smoothing Model for Stock Price Forecasting (2023-2024)

## Overview
This project implements an Exponential Smoothing model to forecast stock prices for the year 2023-2024. The model uses historical stock price data to predict future closing prices, providing insights into potential price movements.

## Dataset
The dataset used for this project is located in the `/dataset` directory. It contains historical stock prices with the following columns:
- **Ticker**: Stock symbol.
- **Date**: The date of the recorded prices.
- **Open**: Opening price of the stock.
- **High**: Highest price of the stock during the day.
- **Low**: Lowest price of the stock during the day.
- **Close**: Closing price of the stock.
- **Volume**: Number of shares traded.

### Dataset Location
- `/dataset/stocks.csv`

## Jupyter Notebook
The analysis and forecasting are performed in the following Jupyter notebook:
- **Exponential Smoothing Model for Stock Price Forecasting (2023-2024).ipynb**

## Requirements
To run this project, ensure you have the following libraries installed:
- `pandas`
- `numpy`
- `matplotlib`
- `statsmodels`
- `scikit-learn`

You can install these libraries using pip:

```bash
pip install pandas numpy matplotlib statsmodels scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/Vishnugnath/Exponential-Smoothing-Model-for-Stock-Price-Forecasting-2023-2024.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Exponential-Smoothing-Model-for-Stock-Price-Forecasting-2023-2024
   ```
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook "Exponential Smoothing Model for Stock Price Forecasting (2023-2024).ipynb"
   ```

4. Run the notebook cells to perform the analysis and view the results.

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
