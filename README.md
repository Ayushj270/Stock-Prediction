## AI Financial Advisor with Stock Prediction

Overview

🎯🎯🎯 This project uses artificial intelligence and machine learning to predict stock price directions while incorporating sentiment analysis of financial news. The app is built using Python and Streamlit for a user-friendly interface.
## Table of content

Key Features

🚀 Historical Stock Data: Retrieves historical stock data for the past year.

📊 Stock Trend Visualization: Displays graphical trends of stock prices over time.

💬 Sentiment Analysis: Analyzes financial news sentiment using both TextBlob and VADER.

🔮 Stock Direction Prediction: Predicts stock movement (up or down) using a RandomForestClassifier.

🖥️ User-Friendly Web Interface: Built with Streamlit for real-time interaction and visualization. 🎯🎯🎯

Technologies Used

🛠️ Python Libraries:

yfinance: Fetch stock market data.

pandas: Handle data manipulation and preprocessing.

matplotlib: Visualize stock trends.

streamlit: Create a web interface for user interaction.

sklearn: Build and evaluate the Random Forest model.

newspaper: Scrape financial news articles.

textblob and vaderSentiment: Perform sentiment analysis. 🛠️🛠️🛠️

Project Workflow

🔍 Input Stock Ticker: The user provides the stock ticker symbol (e.g., AAPL, TSLA). 🎯🎯🎯

📈 Fetch Stock Data: Retrieves one year's worth of stock data and calculates daily price changes.

📰 Fetch Financial News: Scrapes recent news articles related to the provided stock ticker.

🧠 Sentiment Analysis: Analyzes the sentiment of the news data to compute a sentiment score.

🏗️ Train Model: A Random Forest model is trained on historical data to predict stock movement.

🎯 Prediction: Uses the trained model and sentiment score to predict whether the stock will go up or down.

📉 Visualization: Displays historical trends of stock prices. 🎯🎯🎯

How to Use

🎯🎯🎯 1. ⚙️ Install Required Libraries:

pip install yfinance pandas matplotlib streamlit scikit-learn newspaper3k textblob vaderSentiment

▶️ Run the Application:

streamlit run app.py

💡 Interact with the App:

Enter the stock ticker symbol (e.g., AAPL for Apple Inc.).

View sentiment analysis results and stock trend predictions. 🎯🎯🎯

Folder Structure

project-folder/
|—— app.py                  # Main application file
|—— README.md               # Documentation

Notes

🎯🎯🎯 - 🌐 Ensure an active internet connection to fetch stock data and financial news.

🗞️ Sentiment analysis relies on the quality and availability of news articles.

📊 Model accuracy depends on historical data trends and may vary with different stock tickers. 🎯🎯🎯

Future Enhancements

🎯🎯🎯 - 🤖 Integrate deep learning models for improved prediction.

🧮 Add support for multiple stock tickers at once.

🌎 Expand the scope of news analysis to include global financial news. 🎯🎯🎯

Disclaimer

🎯🎯🎯 This tool is for educational purposes only and should not be used for financial decision-making without further analysis. 🎯🎯🎯
