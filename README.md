
# Bitcoin Price Prediction (Next 2 Days) July 19 to July 21
# I done this Project July 18
## Project Overview
This project predicts the **next 2 days of Bitcoin (BTC-USD) prices** using **Machine Learning (ML)** and **Deep Learning (LSTM)** models. 
It compares multiple ML algorithms and selects the best-performing model for forecasting.

## Key Features
- Fetches historical Bitcoin data using Yahoo Finance.
- Performs feature engineering with lagged prices.
- Compares ML models: Linear Regression, Decision Tree, Random Forest, SVR, and KNN.
- Evaluates models using **Mean Squared Error (MSE)** and **R² Score**.
- Uses **Random Forest** as the best model for final forecasting.
- Includes a **2-day forecast pipeline** for Bitcoin prices.
- Provides data visualizations and predictions.

## Project Workflow
1. **Data Collection**: Yahoo Finance BTC-USD price data (1-year period).
2. **Feature Engineering**: Creating lag features.
3. **Model Training & Comparison**: ML algorithms are trained and tested.
4. **Evaluation**: MSE and R² scores are calculated for each model.
5. **Forecasting**: Best model is used to predict the next 2 days of BTC prices.
6. **Visualization**: Plots actual vs predicted prices and final 2-day predictions.

## Results
- **Random Forest** achieved the lowest MSE among all models.
- The model provides accurate 2-day BTC price forecasts.

## How to Use
1. Clone the repository or download the project files.
2. Install the required libraries using:
   ```bash
   pip install -r requirements.txt
   ```
3. Open `btc_ml_price_prediction.ipynb` in Jupyter or Google Colab.
4. Run all cells to train models and generate predictions.

## Files
- `btc_ml_price_prediction.ipynb`: The main notebook with code and results.
- `requirements.txt`: List of Python dependencies.
- `README.md`: Project documentation.

## Future Improvements
- Incorporate more features (technical indicators like RSI, MACD, etc.).
- Use advanced deep learning models (GRU, Transformer-based models).
- Deploy as a web app using **Streamlit** or **Flask**.

## Author
**Mohamed Irfan**  
Data Science & Analytics Enthusiast
