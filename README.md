# Stock Prediction Project

This project provides a simple Python-based solution to predict future stock closing prices using historical data.

## Features

* Predict closing prices for a given stock ticker symbol using Linear Regression.
* Specify the number of future days to forecast.
* Outputs predictions in a clear tabular format.
* Easy to run locally without needing an API.

## Requirements

* Python 3.10+
* Libraries:

  * yfinance
  * pandas
  * numpy
  * scikit-learn

Install the required libraries using:

```bash
pip install yfinance pandas numpy scikit-learn
```

## Usage

1. Download the repository or copy the Python script.
2. Run the Python script in your local environment.
3. Provide the stock ticker and number of days to predict.

### Example

```python
from stock_prediction import predict_next_month

predictions = predict_next_month('AAPL', days=30)
print(predictions)
```

This will output a DataFrame with predicted closing prices for the next 30 days.

## Notes

* Predictions are based on historical data using a simple Linear Regression model.
* This is for educational purposes and not financial advice.

## License

MIT License
