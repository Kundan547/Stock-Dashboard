# Stock-Dashboard
Welcome to the Interactive Stock Dashboard! This Streamlit-based project provides a user-friendly interface for stock analysis. Input a stock ticker and date range to visualize historical prices, analyze performance metrics, access fundamental financial data, and read the latest stock news. Perfect for traders and investors!

# Title: Interactive Stock Dashboard with Streamlit
This project is an advanced Stock Dashboard built using Streamlit, aimed at providing a highly interactive and user-friendly platform for stock analysis. Users can input a stock ticker and specify a date range to visualize the stock's historical pricing data, analyze performance metrics, access fundamental financial data, and read the latest news related to the stock.

# Key Features:
 User-Friendly Input:

Sidebar fields for stock ticker and date range input.
Utilizes Streamlit’s session state to remember selected dates.
Stock Data Visualization:

 Downloads historical stock data from Yahoo Finance.
Interactive line chart displaying the stock's adjusted closing prices using Plotly.
Performance Metrics:

 Calculates annual return, standard deviation, and risk-adjusted return.
Provides a detailed performance analysis of the stock.
Fundamental Data Access:

Retrieves and displays the balance sheet, income statement, and cash flow statement using Alpha Vantage API.
 Latest News Integration:

Fetches top 10 news articles related to the stock from StockNews API.
Displays publication date, title, summary, and sentiment analysis (if available).
Robust Error Handling:

Gracefully handles errors during data download and provides user feedback.
# Technologies Used:
Streamlit: For building the interactive web app.

Pandas and NumPy: For data manipulation and calculations.

Yahoo Finance API: For historical stock data.

Plotly: For interactive charts.

Alpha Vantage API: For financial data.

StockNews API: For latest stock news.


This project leverages multiple APIs to create a robust tool for traders, investors, and analysts, making stock analysis accessible and engaging.
