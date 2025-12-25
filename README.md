📈 Cryptocurrency Price Prediction using Machine Learning
📌 Overview

This project focuses on predicting future cryptocurrency prices using Machine Learning, specifically a Long Short-Term Memory (LSTM) deep learning model. The model analyzes historical Bitcoin (BTC-USD) price data to learn time-series patterns and forecast the next closing price.

Cryptocurrency markets are highly volatile and non-linear, making traditional prediction methods less effective. By leveraging LSTM networks, this project captures long-term dependencies in sequential data, enabling more reliable price forecasting.

🎯 Problem Statement

Cryptocurrency prices change rapidly and unpredictably

High volatility and sequential dependencies make forecasting difficult

Investors and analysts need data-driven tools to understand price trends

This project addresses these challenges by applying deep learning-based time-series forecasting.

🧠 Model Logic (Simple Explanation)

Historical Bitcoin price data is collected and sorted by date

The data is normalized to bring values into a comparable range

The time-series data is converted into sequences so the model can learn from past prices

An LSTM neural network is trained on this sequential data

The model learns patterns and trends from historical prices

Predictions are generated for future closing prices

Results are evaluated by comparing actual vs predicted prices

🔄 Data & Workflow

Collected historical BTC-USD price data (CSV format)

Performed data preprocessing:

Feature selection (price values)

Normalization using scaling techniques

Sequence generation for LSTM input

Split data into training and testing sets

Built and trained an LSTM model using TensorFlow/Keras

Generated predictions on test data

Visualized model performance using actual vs predicted price graphs

🖥️ Web-Based Demo

This project also includes a simple web interface where:

Users enter the current Bitcoin closing price

The trained model predicts the next closing price

The predicted value is displayed instantly

This demonstrates how a machine learning model can be integrated into a user-facing application.

🛠️ Tech Stack

Programming Language: Python

Machine Learning: LSTM (TensorFlow / Keras)

Data Processing: Pandas, NumPy

Visualization: Matplotlib

Environment: Jupyter Notebook

Dataset: Historical Bitcoin (BTC-USD) price data

▶️ How to Run Locally
1️⃣ Clone the Repository
git clone https://github.com/your-username/crypto-price-prediction.git
cd crypto-price-prediction

2️⃣ Install Dependencies
pip install numpy pandas matplotlib tensorflow

3️⃣ Run the Notebook
jupyter notebook


Open MAIN_prediction.ipynb

Run all cells to train the model and view predictions

📊 Results

The LSTM model successfully captures overall price trends

Predictions follow the general movement of actual Bitcoin prices

Short-term volatility is smoothed, which is typical for deep learning models

Results are visualized using Actual vs Predicted Price plots

📚 Learning Outcomes

Hands-on experience with time-series forecasting

Practical understanding of LSTM neural networks

Data preprocessing and normalization techniques

Model training, evaluation, and visualization

Integration of machine learning models into applications

🚀 Future Improvements

Add multiple features (volume, indicators, sentiment data)

Improve accuracy using hyperparameter tuning

Support multiple cryptocurrencies

Enable real-time data fetching using APIs

👤 Author
Aadarsh Krishna
📧 aadarshkrishna2000@gmail.com
