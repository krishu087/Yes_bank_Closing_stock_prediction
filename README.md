# 📉 Yes Bank Stock Price Prediction using Linear Regression

This project aims to analyze and predict the **monthly closing stock price** of Yes Bank using historical stock data. The focus is on understanding how events like the 2018 fraud case impacted the stock and evaluating whether simple machine learning models can capture such trends.

---

## 📌 Problem Statement

Yes Bank, a key player in the Indian banking sector, saw significant fluctuations in its stock prices — particularly after 2018 due to financial fraud involving its co-founder. This project addresses the question:

> Can we accurately predict the monthly **closing price** of Yes Bank stock using historical data like `Open`, `High`, and `Low`?

---

## 🎯 Objective

- Analyze monthly stock price data of Yes Bank.
- Understand price behavior before and after 2018.
- Build and evaluate a **Linear Regression** model to predict the closing price.
- Visualize insights using charts and plots.

---

## 📊 Dataset Information

- **Source**: CSV file containing monthly stock data of Yes Bank.
- **Columns**:
  - `Date`: Month and Year (e.g., Jan-19)
  - `Open`: Opening price of the month
  - `High`: Highest price of the month
  - `Low`: Lowest price of the month
  - `Close`: Closing price of the month (Target Variable)

---

## 🧹 Data Preprocessing

- Converted `Date` to datetime format
- Sorted data chronologically
- Handled missing values using **forward fill**
- Removed outliers using **IQR method**
- Checked unique values and data summary

---

## 📈 Exploratory Data Analysis (EDA)

- **Line Chart** of Closing Prices over time
- **Correlation Heatmap** between features
- **Pair Plot** to visualize feature relationships
- Observed a sharp decline in prices after 2018

---

## 🤖 ML Model Used

### Linear Regression
- Features: `Open`, `High`, `Low`
- Target: `Close`
- Evaluation Metrics:
  - **MAE**
  - **RMSE**
  - **R² Score**

This model served as a **baseline** with strong initial performance.

---

## 📌 Key Insights

- Strong correlation between `Open`, `High`, `Low` and `Close`.
- Sharp decline in stock price post-2018 event.
- Linear Regression achieved high R² value (~0.92).

---

## ✅ Conclusion

The project demonstrated how simple machine learning models like **Linear Regression** can predict stock closing prices with good accuracy. It also highlighted the effect of real-world events on stock behavior. This baseline can be further improved using more advanced models like **Random Forest**, **XGBoost**, or **LSTM**.

---

## 🚀 Future Work

- Try advanced ML models (Random Forest, XGBoost, etc.)
- Include external features like news sentiment, financial reports
- Extend to daily data for finer analysis

---

## 📂 Folder Structure

├── data_YesBank_StockPrices.csv
├── YesBank_StockPrice_Prediction_Submission.ipynb
├── README.md

## 👨‍💻 Author

**Krishna Panjre**  
*Data Science Enthusiast | Python | Machine Learning | Stock Analysis*

---

## 📄 License

This project is open-source and free to use for educational purposes.
