# TCS-Stock-Price-Forecasting-using-ARIMA-model

1)Took the real-time stock prices of TCS from NATIONAL STOCK EXACHANGE(NS) using "yfinance" package.
2)Then current date, date before 2 years and tomorrow's date have been calculated using "datetime" package.
3)Then the required EDA is done, like PARTIAL AUTO CORRELATION AND AUTO CORRELEATION plots etc.,that are required for a ideal ARIMA model.
4)Also the "Percentage Returns" have been calculated using the stock prices.
5)Then ARIMA model was successfully built on the Stock Prices,and the correlation between predicted and actual prices have been visualized clearly.
6)Additionally, a SARIMAX model was built on the Percentage Returns,and the correlation between predicted and actual returns have been visualized clearly.
7)Then the Stock price forecasting model(i.e ARIMA model) is saved using joblib.
8)The model's forecasted price was VERY MUCH SIMILAR with the real-time TCS.NS[ Refer https://www.reuters.com/markets/companies/TCS.NS ]
