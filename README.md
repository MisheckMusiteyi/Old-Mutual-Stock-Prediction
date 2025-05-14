# Old-Mutual-Stock-Prediction
This project analyzes Old Mutual’s stock price trends on the London Stock Exchange (LSE) using ARIMA modeling for time series forecasting. 
Old Mutual Stock Prediction Using ARIMA
📌 Project Overview
This project applies ARIMA (AutoRegressive Integrated Moving Average) modeling to forecast Old Mutual’s stock price trends on the London Stock Exchange (LSE). It aims to analyze stock behavior using time series forecasting, focusing on improving prediction accuracy and handling market volatility.

📊 Data Collection
Source: Historical stock data obtained from Investing.com.

Time Period: The dataset spans several years of daily stock prices.

Features Used: Date, Price, Open, High, Low, Volume, and Change %.

🔧 Methods & Techniques
✔ Data Preprocessing – Cleaning missing values, handling stationarity, and applying differencing. ✔ ARIMA Model Implementation – Selecting optimal (p, d, q) parameters using ADF tests and ACF/PACF plots. ✔ Walk-Forward Validation – Evaluating performance through rolling predictions. ✔ Error Metrics – Assessing forecasting accuracy with Mean Absolute Error (MAE). ✔ Residual Diagnostics – Ensuring model residuals are centered around zero with white noise behavior.

📈 Results & Findings
ARIMA captures stock trends effectively but struggles in high volatility scenarios.

MAE analysis confirms model accuracy in predicting stock movements.

Future improvements include SARIMA for seasonality and hybrid deep learning approaches.

🛠 How to Run the Notebook
1️⃣ Clone this repository:

git clone https://github.com/MisheckMusiteyi/Old-Mutual-Stock-Prediction.git
2️⃣ Install dependencies:

bash
pip install pandas numpy statsmodels scikit-learn matplotlib seaborn
3️⃣ Open Jupyter Notebook and run Old-Mutual-Stock-Prediction.ipynb.

🏆 Future Enhancements
🔹 Incorporate SARIMA for seasonal trend modeling. 🔹 Experiment with LSTM Neural Networks for deep learning-based forecasting. 🔹 Optimize hyperparameters using Grid Search or Auto-ARIMA for enhanced accuracy.
