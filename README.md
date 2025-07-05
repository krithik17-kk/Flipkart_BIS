# Flipkart Business Intelligence Suite (FBIS)

## 📊 Project Overview
The Flipkart Business Intelligence Suite (FBIS) is an end-to-end data analytics and visualization project designed to simulate a real-world e-commerce analytics environment. Using Power BI and Python, this project delivers actionable insights across sales, customer segments, product performance, and fraud detection for Flipkart.

## 🧠 Objective
To build an interactive dashboard and analytical pipeline that empowers Flipkart stakeholders with:
- Daily revenue trends
- Top product performance
- Customer segmentation using RFM analysis
- Detection of potentially fraudulent transactions

## 🗂️ Dataset Summary
The project uses synthetic but realistic data across four dimensions:

| File | Description |
|------|-------------|
| `daily_sales.csv` | Daily revenue data (date-wise trends) |
| `top_products.csv` | Top 10 products based on sales amount |
| `customer_segments.csv` | RFM scores with customer segments |
| `potential_frauds.csv` | Transactions flagged as potential fraud |

## 📌 Tools Used
- **Power BI** – Dashboard and report creation
- **Python (Jupyter Notebook)** – Time series forecasting using ARIMA (SARIMAX)
- **Libraries** – pandas, matplotlib, statsmodels, seaborn

## 📈 Dashboard Insights
- **Sales Trend:** Daily revenue fluctuations over time
- **Product Analysis:** Top performing products by total sales
- **Customer Segments:** Champions, Loyal, At Risk, Lost, etc. (RFM-based)
- **Fraud Watch:** List and visualization of suspicious transactions

## 🔬 Forecasting Model
A SARIMAX model is used for daily sales forecasting. The notebook includes:
- Stationarity check using ADF test
- ACF and PACF plots
- SARIMAX model fitting
- Future revenue prediction

## 🖥️ How to Run
### Jupyter Notebook (For Forecasting)
1. Install dependencies: `pip install -r requirements.txt`
2. Open notebook: `jupyter notebook notebooks/sales_forecast.ipynb`
3. Run all cells for EDA and forecasting

### Power BI
1. Open `Flipkart_BIS.pbix` in Power BI Desktop
2. Explore all dashboards

## 📂 Folder Structure
```
Flipkart_BIS/
│
├── notebooks/
│   └── sales_forecast.ipynb
│
├── data/
│   ├── daily_sales.csv
│   ├── top_products.csv
│   ├── customer_segments.csv
│   └── potential_frauds.csv
│
├── Flipkart_BIS.pbix
├── requirements.txt
└── README.md
```

## 👨‍💻 Author
Krithik Krithik  
[LinkedIn](https://www.linkedin.com/in/krithik17) • [GitHub](https://github.com/krithik17-kk)

## 🚀 Future Scope
- Add real Flipkart API data (if available)
- Incorporate predictive analytics for customer churn
- Build a real-time fraud alert system

---
> 📢 **Feel free to fork or star the repo if you found it helpful!**
