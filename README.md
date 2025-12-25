Cryptocurrency Price Prediction using Machine Learning

Overview
This project focuses on predicting future cryptocurrency prices using Machine Learning, specifically a Long Short-Term Memory (LSTM) deep learning model. The model analyzes historical Bitcoin (BTC-USD) price data to learn time-series patterns and forecast the next closing price.

Problem Statement
Cryptocurrency markets are highly volatile and non-linear, making traditional prediction methods less effective. This project applies deep learning-based time-series forecasting to address these challenges.

Model Logic
1. Collect and sort historical Bitcoin price data
2. Normalize the data
3. Convert time-series data into sequences
4. Train an LSTM neural network
5. Generate future price predictions
6. Evaluate results using actual vs predicted prices

Data & Workflow
- Historical BTC-USD price data (CSV)
- Data preprocessing (normalization, sequencing)
- Train-test split
- LSTM model training
- Visualization of predictions

Web-Based Demo
Users can input the current Bitcoin closing price to predict the next closing price using the trained ML model.

Tech Stack
- Python
- LSTM (TensorFlow / Keras)
- Pandas, NumPy
- Matplotlib
- Jupyter Notebook

Learning Outcomes
- Time-series forecasting
- Deep learning with LSTM
- Data preprocessing
- Model evaluation and visualization

Future Improvements
- Add more features
- Support multiple cryptocurrencies
- Real-time API integration

Author
Aadarsh Krishna
