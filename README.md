# 🚀 Equal-Weight S&P 500 Index Fund Algorithmic Trading Script

Welcome to the Equal-Weight S&P 500 Index Fund Algorithmic Trading Script! This Python-powered tool empowers you to effortlessly build an equal-weighted portfolio of S&P 500 stocks, optimizing your investment strategy with ease.

## ✨ Features

- **S&P 500 Constituents**: Automatically fetches the latest list of S&P 500 constituent stocks.
- **Real-Time Data**: Retrieves up-to-the-minute data for each stock, including price and market capitalization, via the IEX Cloud API.
- **Portfolio Customization**: Calculates the precise number of shares to buy for each stock based on your portfolio's value.
- **Efficient Processing**: Utilizes batch API calls for lightning-fast performance.
- **Sleek Output**: Generates a beautifully formatted Excel file containing recommended trades.

## 🛠️ Usage

1. **Get Started**: Clone or download the script files.
2. **Dependencies**: Install the required dependencies listed in `requirements.txt`.
3. **API Token**: Obtain an API token from IEX Cloud and securely store it in a file named `secrets.py`.
4. **Run the Script**: Launch the script and input the value of your portfolio when prompted.
5. **Get Recommendations**: Sit back and watch as the script generates an Excel file (`recommended trades.xlsx`) packed with tailored recommendations for your ideal S&P 500 portfolio.

## 📋 Requirements

To install the required dependencies, run the following command:

```bash
pip install -r requirements.txt
```

- Pandas
- Requests
- XlsxWriter

## ⚠️ Disclaimer

This script is an educational tool meant for exploration and learning purposes. It is not financial advice. Before making any investment decisions, conduct thorough research and consider seeking guidance from a qualified financial advisor.

## 🌟 Let's Get Investing!

Dive into the world of algorithmic trading and equal-weight investing with the Equal-Weight S&P 500 Index Fund Algorithmic Trading Script. Happy learning!
