This project implements a trading strategy using Gaussian Copulas to model the relationship between Gold (GLD) and the US Dollar Index (DXY)
- Download and preprocess historical price data with `yfinance`
- Fit a Gaussian copula to model joint returns
- Generate buy signals based on USD weakness and gold return probabilities
- Apply stop-loss, take-profit, commission, and slippage
- Track capital growth compared to buy-and-hold
