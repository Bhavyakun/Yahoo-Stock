# Stock Market Analysis & Forecasting

## 📌 Project Overview
This project analyzes historical stock price data to identify trends, volatility, and patterns using **data analytics and machine learning**. It implements **statistical models (ARIMA, Moving Averages)** and **deep learning models (LSTM)** to forecast stock prices and provide **actionable business insights**.

## 🎯 Objectives
- Perform **data wrangling** and clean financial datasets.
- Conduct **exploratory data analysis (EDA)** to identify stock trends and volatility.
- Use **visualizations** (Matplotlib, Seaborn, Plotly) to interpret market movements.
- Implement **time-series forecasting models**: ARIMA, Facebook Prophet, LSTM.
- Extract **business insights** to assist investors in decision-making.

## 📊 Dataset
- **Source:** Yahoo Finance Historical Stock Data
- **Attributes:** Date, Open, High, Low, Close, Adj Close, Volume
- **Time Period:** 5 years (daily stock prices)

## 🛠️ Tools & Technologies
- **Python**: Pandas, NumPy, Scikit-learn
- **Data Visualization**: Matplotlib, Seaborn, Plotly
- **Statistical Models**: Moving Averages, ARIMA, Prophet
- **Deep Learning**: TensorFlow/Keras (LSTM)
- **Forecasting Frameworks**: Statsmodels, Facebook Prophet

## 🔍 Exploratory Data Analysis (EDA)
- **Stock Trends**: Analyzing closing price over time.
- **Volatility Analysis**: Computing standard deviations for risk assessment.
- **Moving Averages**: Identifying trends using 20-day, 50-day, and 100-day MAs.
- **Correlation Heatmap**: Evaluating relationships between stock attributes.

## 📈 Forecasting Models
### 1️⃣ **ARIMA (AutoRegressive Integrated Moving Average)**
- Short-term forecasting
- Captures linear trends and seasonality
- Applied to closing prices with hyperparameter tuning

### 2️⃣ **Facebook Prophet**
- Detects seasonality and trend patterns
- Generates long-term stock price predictions
- Useful for financial planning and investment strategies

### 3️⃣ **LSTM (Long Short-Term Memory)**
- Deep learning-based sequence prediction
- Learns complex price patterns from historical data
- Provides high-accuracy stock price forecasting

## 📊 Results & Business Insights
- **Stock trends follow cyclical patterns**, visible in moving averages and Prophet forecasts.
- **Short-term predictions using ARIMA** are accurate but limited for volatile stocks.
- **Long-term forecasts using LSTM** capture trends effectively, improving decision-making.
- **Investors should use a combination of statistical models and AI** for robust predictions.

## 🚀 How to Run the Project
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Bhavyakun/Yahoo-Stock.git
cd Yahoo-Stock
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Jupyter Notebook
```bash
jupyter notebook
```
Open `YahooStock.ipynb` and execute the cells.

## 📌 Future Enhancements
✅ Integrate **macroeconomic indicators** (inflation, interest rates) for better accuracy.  
✅ Explore **Reinforcement Learning** for automated stock trading strategies.  
✅ Implement **ensemble methods** (ARIMA + LSTM + Prophet) for robust forecasting.  

## 📜 License
This project is licensed under the **MIT License**.

---
🔗 **Connect with Me**: [LinkedIn](https://www.linkedin.com/in/bhavya-sharma-207550173//) | [GitHub](https://github.com/bhavyakun/)

