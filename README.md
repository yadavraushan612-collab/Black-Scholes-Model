# Black-Scholes-Model-for-Option-Pricing
In this project I implemented Black-Scholes Model for Option Pricing of Duolingo (DUOL) leveraging yfinance and python libraries.

# About Project
Here I utilised yfinance, numpy, matplotlib, etc. packages of python for efficient Scraping of Historical Data, Graphical Analysis.\
>
>
<h2> yfinance Library </h2>
The yfinance library is a Python library that provides an easy and efficient way to retrieve stock data, including option chains, from Yahoo Finance.\
To retrieve the option chain for Duolingo (DUOL), I defined following function:

![image](https://github.com/paras07/Black-Scholes-Model-for-Option-Pricing/assets/33325793/1acbcabf-c426-461d-a2a6-e8fe918e8df7)

# Black-Scholes Model

The Black-Scholes model is a financial model used to calculate the fair price or theoretical value for a European call or put option, using assumptions of constant volatility, no dividends, and efficient markets. 

<h3> Call Option Price = (Stock Price × N(d1)) - (Strike Price × e^(-rt) × N(d2)) </h3>

![image](https://github.com/paras07/Black-Scholes-Model-for-Option-Pricing/assets/33325793/aa3175ff-bb6c-4444-9930-6a3765144327)

- The Black-Scholes model requires five input variables: the strike price of an option, the current stock price, the time to expiration, the risk-free rate, and the volatility.
- With these variables, it is theoretically possible for options sellers to set rational prices for the options that they are selling.
- Model predicts that the price of heavily traded assets follows a geometric Brownian motion with constant drift and volatility.
- When applied to a stock option, the model incorporates the constant price variation of the stock, the time value of money, the option's strike price, and the time to the option's expiry.

# Benefits and Limitations of Black Scholes Model

![image](https://github.com/paras07/Black-Scholes-Model-for-Option-Pricing/assets/33325793/ac7a9b9d-ca13-4064-954b-cd87507315da)

cc:_Investopedia_
