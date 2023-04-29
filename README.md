# Торговый бот

Торговый бот, суть которого заключается в автоматической торговле разными крипто-монетами на платформе Binance. Работает с приминением метода градиентного бустинга, но в данный момент была поставлена цель усовершенствовать алгоритм, применив рекуррентные нейронные сети.
Идея алгоритма сведена к задаче классификации. Классы следующие - 1, если в течении следующих n дней цена монеты поднимется выше заданного процента, и 0 иначе.

get_hours.ipynb и get_crypto_data.ipynb - скрипты, работающие с API Бинанса и получащие все необходимые данные для модели

catboost_forest.ipynb - скрипт, создающий модель

trading_bot.ipynb - главный скрипт, активирующий бота

_____________________________________________________________________________________________

# Trading bot

A trading bot, which can automatically earns money by trading crypto on Binance. Works on Catboost, now i'm trying to complicate my method with the help of LSTM nn. 
The idea is that algorythm predicts, if there is a chance for the price of a coin to go up in the next N days, and it buys it, if so. Then it sells all when the price raises on some %.

get_hours.ipynb and get_crypto_data.ipynb - files that works with the API of Binance and creates data for future models

catboost_forest.ipynb - creates models based on prepared data

trading_bot.ipynb - main script, that activates a trading algorithm and works until you stop it

Now this project is closed for several months, because i need to check some new ideas on implementing nn in this alg and also i want to make an analysis of the latest news about the target coin to minimize the final error.
