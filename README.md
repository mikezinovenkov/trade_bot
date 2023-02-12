# trade_bot
A trading bot, which can automatically earns money by trading crypto in binance. Works on Catboost, now i'm trying to complicate my method with the help of LSTM nn. The idea is that algorythm predicts, if there is a rise in the price of a coin, and it buys it, if so. Then it sells all when the price raises on some %.

get_hours.ipynb and get_crypto_data.ipynb - files that create and prepare data for future models

catboost_forest.ipynb - creates models based on prepared data

trading_bot.ipynb - main script, that activates a trading algorithm and works until you stop it
