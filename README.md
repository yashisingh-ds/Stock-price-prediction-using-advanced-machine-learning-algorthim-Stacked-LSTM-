# Stock-price-prediction-using-advanced-machine-learning-algorthim-Stacked-LSTM

# 📝 Project Overview
In this project, I have worked on predicting the stock prices of Tesla using a Stacked LSTM model, an advanced deep learning technique. The dataset used for this project was sourced from Kaggle and includes Tesla's historical stock prices.The goal of this project is to build a predictive model that accurately forecasts stock prices, leveraging the Stacked Long Short-Term Memory (LSTM) neural network for time series data. This project highlights how advanced machine learning models can significantly improve prediction accuracy compared to traditional models.

# 📂 Dataset Details
-**Dataset Name**: Tesla Stock Prices
-**Source:** Kaggle
-**Data Type:** Time-series data
-**Key Features:** Date, Open, High, Low, Close, Volume

# 🧪 Model Used
The primary machine learning model used in this project is:
**Stacked LSTM (Long Short-Term Memory):** A type of Recurrent Neural Network (RNN) well-suited for time series prediction tasks.
LSTM models are known for their ability to capture long-term dependencies in sequential data. In this project, a stacked version of LSTM was used to enhance the model's capacity to learn complex patterns in stock price movements over time.

# 📊 Evaluation Metrics and Model Performance
The performance of the Stacked LSTM model was evaluated using two key metrics:
-**R-squared (R²):** This metric measures how well the predicted values match the actual values. A higher R² value indicates that the model explains more variance in the stock prices. In this project, the R² value for the training set was approximately 95.14%, indicating that the model captured most of the variance in the training data.
-**MAPE (Mean Absolute Percentage Error):** This metric provides an average percentage error between the predicted and actual values. A lower MAPE value indicates better accuracy. The model achieved a low MAPE score, suggesting highly accurate predictions.
Overall, the model achieved an impressive training accuracy of 95.14% and test set accuracy of 94.74%, demonstrating its effectiveness in capturing both linear and non-linear patterns in the data.

# 🚀 Technologies and Libraries Used
-**Python** 
-**pandas**
-**numpy**
-**matplotlib**
-**seaborn**
_**scikit-learn**
-**TensorFlow**
-**Keras**

# 🛠️ How to Run the Project
**Clone the repository:**
git clone https://github.com/yashisingh-ds/stock-price-prediction.git

# 📚 Key Findings
The Stacked LSTM model effectively captures both linear and non-linear patterns in the stock price data.The model achieved an impressive training accuracy of 95.14% and test set accuracy of 94.74%.
The predictions closely match the actual stock prices, as shown in the plot, indicating strong performance of the model.



