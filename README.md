# LSTM Stock Prediction for S&P 500

This repository contains a Jupyter notebook that demonstrates how to use Long Short-Term Memory (LSTM) neural networks to predict stock prices for the S&P 500 index. The notebook covers the following steps:

- Importing libraries and data
- Exploratory data analysis and visualization
- Data preprocessing and feature engineering
- Building and training the LSTM model
- Evaluating the model performance and making predictions
- Conclusion and future work

The data used in this project is obtained from Yahoo Finance and contains the daily closing prices of the S&P 500 index from January 1st, 2010 to December 31st, 2020. The LSTM model is implemented using TensorFlow and Keras.

The main goal of this project is to showcase how LSTM networks can capture the temporal dependencies and patterns in time series data, such as stock prices, and provide accurate forecasts for future values. However, this project is not intended to provide any financial advice or recommendations for trading or investing in stocks.

![image](https://user-images.githubusercontent.com/25248102/220925879-06ca42fa-b6c2-47bf-b5b4-0ea5347c2b49.png)

## Usage

View the notebook directly on GitHub, read the [PDF export](LSTM-price-prediction-sp500.pdf), or open it in [Google Colab](https://colab.research.google.com/github/arogan178/lstm-stock-prediction-sp500/blob/master/LSTM-price-prediction-sp500.ipynb).

To run it locally:

```sh
git clone https://github.com/arogan178/lstm-stock-prediction-sp500.git
cd lstm-stock-prediction-sp500
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt jupyter
jupyter notebook LSTM-price-prediction-sp500.ipynb
```

## License
[MIT](LICENSE)
