📈 Cryptocurrency Price Prediction using Machine Learning
📌 Overview
This project focuses on predicting future cryptocurrency prices using Machine Learning, specifically a Long Short-Term Memory (LSTM) deep learning model. The model analyzes historical Bitcoin (BTC-USD) price data to learn time-series patterns and forecast the next closing price.
Cryptocurrency markets are highly volatile and non-linear, making traditional prediction methods less effective. By leveraging LSTM networks, this project captures long-term dependencies in sequential data, enabling more reliable price forecasting.
________________________________________
🎯 Problem Statement
•	Cryptocurrency prices change rapidly and unpredictably
•	High volatility and sequential dependencies make forecasting difficult
•	Investors and analysts need data-driven tools to understand price trends
This project addresses these challenges by applying deep learning-based time-series forecasting.
________________________________________
🧠 Model Logic (Simple Explanation)
1.	Historical Bitcoin price data is collected and sorted by date
2.	The data is normalized to bring values into a comparable range
3.	The time-series data is converted into sequences so the model can learn from past prices
4.	An LSTM neural network is trained on this sequential data
5.	The model learns patterns and trends from historical prices
6.	Predictions are generated for future closing prices
7.	Results are evaluated by comparing actual vs predicted prices
________________________________________
🔄 Data & Workflow
•	Collected historical BTC-USD price data (CSV format)
•	Performed data preprocessing:
o	Feature selection (price values)
o	Normalization using scaling techniques
o	Sequence generation for LSTM input
•	Split data into training and testing sets
•	Built and trained an LSTM model using TensorFlow/Keras
•	Generated predictions on test data
•	Visualized model performance using actual vs predicted price graphs
________________________________________
🖥️ Web-Based Demo
This project also includes a simple web interface where:
•	Users enter the current Bitcoin closing price
•	The trained model predicts the next closing price
•	The predicted value is displayed instantly
This demonstrates how a machine learning model can be integrated into a user-facing application.
________________________________________
🛠️ Tech Stack
•	Programming Language: Python
•	Machine Learning: LSTM (TensorFlow / Keras)
•	Data Processing: Pandas, NumPy
•	Visualization: Matplotlib
•	Environment: Jupyter Notebook
•	Dataset: Historical Bitcoin (BTC-USD) price data
________________________________________
▶️ How to Run Locally
1️⃣ Clone the Repository
git clone https://github.com/your-username/crypto-price-prediction.git
cd crypto-price-prediction
2️⃣ Install Dependencies
pip install numpy pandas matplotlib tensorflow
3️⃣ Run the Notebook
jupyter notebook
•	Open MAIN_prediction.ipynb
•	Run all cells to train the model and view predictions
________________________________________
📊 Results
•	The LSTM model successfully captures overall price trends
•	Predictions follow the general movement of actual Bitcoin prices
•	Short-term volatility is smoothed, which is typical for deep learning models
•	Results are visualized using Actual vs Predicted Price plots
________________________________________
📚 Learning Outcomes
•	Hands-on experience with time-series forecasting
•	Practical understanding of LSTM neural networks
•	Data preprocessing and normalization techniques
•	Model training, evaluation, and visualization
•	Integration of machine learning models into applications
________________________________________
🚀 Future Improvements
•	Add multiple features (volume, indicators, sentiment data)
•	Improve accuracy using hyperparameter tuning
•	Support multiple cryptocurrencies
•	Enable real-time data fetching using APIs
________________________________________
👤 Author
Aadarsh Krishna
📧 aadarshkrishna2000@gmail.com

Comparison of actual vs predicted Bitcoin prices over time.
The chart shows how the LSTM model’s predicted prices (red) track the overall trend of actual Bitcoin prices (green), capturing major movements while smoothing short-term volatility.
<img width="1223" height="659" alt="Screenshot 2025-12-25 204858" src="https://github.com/user-attachments/assets/cc4de33f-5a81-4005-b1d5-1d7131625674" />

Web-based Bitcoin price prediction interface.
Users enter the current closing price to generate the next predicted Bitcoin closing price using a machine learning model.
<img width="1067" height="456" alt="Screenshot 2025-12-25 205454" src="https://github.com/user-attachments/assets/cec6cf43-3a51-4a11-81fc-2cdb5dbb2e2a" />

