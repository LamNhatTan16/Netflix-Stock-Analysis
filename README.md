# Netflix Stock Analysis Project

## 📌 Introduction
This project analyzes Netflix stock data to gain insights into its financial performance and risk metrics. We use Python to clean, process, visualize data, and calculate key financial indicators.

## 📊 Dataset Information
- **Source**: [Kaggle - Netflix Complete Stock Data](https://www.kaggle.com/datasets/matiflatif/netflix-complete-stock-dataweekly-updated)
- **File Format**: CSV
- **Key Columns**:
  - `Date`: The date of stock trading.
  - `Open`: Opening price.
  - `Close`: Closing price.
  - `High`: Highest price.
  - `Low`: Lowest price.
  - `Volume`: Number of shares traded.

## 🚀 Project Steps
### **1. Data Collection**
- The dataset was downloaded from Kaggle and saved as `datasets/NFLX.csv`.

### **2. Data Preparation & Processing**
- Remove duplicate records.
- Handle missing values.
- Convert the `Date` column into a proper datetime format.

### **3. Financial Indicators Calculation**
- Compute **Daily Return**: Percentage change in stock price compared to the previous day.

### **4. Risk Analysis**
- Calculate **Value at Risk (VaR)**: Measures potential loss at a given confidence level.
- Compute **Conditional Value at Risk (CVaR)**: Expected loss in extreme cases.

### **5. Data Visualization**
- Plot **Netflix stock price over time** using Matplotlib.

### **6. Save & Export Data**
- Save the processed dataset as `processed_data.csv` for further analysis.

## ⚡ How to Run the Project
### **Requirements**
Make sure you have the following installed:
- Python 3
- Pandas
- NumPy
- Matplotlib

## 📈 Sample Output
```bash
Risk Metrics: {'Mean Return': 0.0012, 'Standard Deviation': 0.02, 'Value at Risk (VaR)': -0.03, 'Conditional VaR (CVaR)': -0.05}
Dữ liệu đã được lưu tại: datasets/processed_data.csv
```

## 📌 Conclusion
- This project provides insights into Netflix stock trends and risk levels.
- The **VaR and CVaR** values help in assessing potential losses.
- The code can be extended to analyze other stocks or timeframes.

## 📂 Project Structure
```
📁 Personal-Project/
│-- 📄 stock_analysis.py  # Main script
│-- 📄 README.md  # Project documentation
│-- 📂 datasets/
│   │-- NFLX.csv  # Raw stock data
│   │-- processed_data.csv  # Cleaned and analyzed data
```

## 📌 Future Improvements
- Incorporate **Moving Averages** for trend analysis.
- Add **Machine Learning models** for stock price prediction.
- Automate data collection using Kaggle API.


