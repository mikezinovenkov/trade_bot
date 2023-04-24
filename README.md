# trade_bot
A trading bot, which can automatically earns money by trading crypto in binance. Works on Catboost, now i'm trying to complicate my method with the help of LSTM nn. The idea is that algorythm predicts, if there is a chance for the price of a coin to go up in the next N days, and it buys it, if so. Then it sells all when the price raises on some %.

get_hours.ipynb and get_crypto_data.ipynb - files that works with the API of Binance and creates data for future models

catboost_forest.ipynb - creates models based on prepared data

trading_bot.ipynb - main script, that activates a trading algorithm and works until you stop it

Now this project is closed for several months, because i need to check some new ideas on implementing nn in this alg and also i want to make an analysis of the latest news about the target coin to minimize the final error.
