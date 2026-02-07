Introduction (Project Intro)

This project is about Stock Market Real-Time Time Series Forecasting.
The main aim of this program is to predict future stock prices (especially the Close price) using Machine Learning and Deep Learning models such as LSTM and Attention LSTM.

Stock market data is time-based (Time Series data). So instead of normal machine learning models, LSTM (Long Short-Term Memory) deep learning models are used because they can learn patterns from past time data and give better predictions.

In this project, both Basic LSTM and Attention LSTM models are implemented and compared to find which gives better prediction accuracy.

Main concepts used in this project:

Data Preprocessing

Feature Engineering

Time Series Sequence Creation

LSTM Deep Learning Model

Attention Mechanism

Evaluation Metrics (MAE, RMSE, MAPE)

✅ Summary (Project Summary)

In this program, first the stock market dataset is loaded and cleaned.
Then, to improve prediction accuracy:

✔ Moving Average features are created
✔ Previous day close prices (Lag features) are added
✔ Data scaling is done using MinMaxScaler

After preprocessing:

Time step sequence data is created

Data is split into training and testing sets

Then two models are trained:

1️⃣ Baseline LSTM Model – Basic deep learning stock prediction model
2️⃣ Attention LSTM Model – Gives more importance to useful time steps and improves prediction accuracy

Then both models are evaluated using:

MAE (Mean Absolute Error)

RMSE (Root Mean Square Error)

MAPE (Mean Absolute Percentage Error)

Finally, graphs are plotted to compare actual stock prices vs predicted prices.

👉 Result:
Attention LSTM usually gives better prediction accuracy compared to normal LSTM.
