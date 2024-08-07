# Stock_pridiction_app
Stock Forecast App
This is a Streamlit-based web application for forecasting stock prices using historical data and the Prophet model. The application allows users to select a stock, specify the number of years for prediction, and visualize the forecast along with historical data.

Features
Stock Selection: Choose from a predefined list of stocks (GOOG, AAPL, MSFT, GME) for prediction.
Prediction Duration: Adjust the number of years for forecasting.
Historical Data: View raw historical data including opening and closing prices.
Forecast Plot: Visualize the forecasted stock prices using Plotly.
Forecast Components: Analyze different components of the forecast such as trend and seasonality.
Installation


To run this application, you need to have Python 3.x installed. Install the required packages using pip:

Copy code
pip install streamlit fbprophet yfinance plotly
Usage
Clone this repository:


Copy code
git clone https://github.com/yourusername/stock-forecast-app.git

Navigate to the project directory:

Copy code
cd stock-forecast-app

Run the Streamlit app:

Copy code
streamlit run app.py

Open the provided local URL in your web browser to interact with the application.

Code Explanation
Imports: The application uses streamlit for the web interface, yfinance for fetching stock data, fbprophet for forecasting, and plotly for plotting.
Data Loading: Historical stock data is fetched using yfinance and cached for performance.
Data Visualization: Historical data and forecasted results are visualized using Plotly.
Forecasting: The Prophet model is used to predict future stock prices based on historical data.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Streamlit
Prophet
yfinance
Plotly
Feel free to customize this README further based on your specific needs or preferences.
