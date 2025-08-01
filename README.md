# 💼 Dynamic Risk-Adjusted Portfolio Rebalancing Tool

A solo-built data-driven investment analytics tool that dynamically rebalances investor portfolios using **macroeconomic indicators from FRED (Federal Reserve Economic Data)** and personalized risk profiles.

> 🔍 Designed and developed to explore the intersection of **data analytics** and **wealth management** — showcasing financial decision-making powered by real-world economic indicators.

---

## 📌 Key Features

- Accepts investor profile inputs (age, risk level, capital)
- Uses live macroeconomic indicators from FRED
- Scores economic conditions (inflation, bond yield, unemployment, GDP)
- Suggests dynamic asset allocations (Equity, Debt, Gold, Liquid)
- Calculates custom risk score and Sharpe Ratio
- Displays results via an interactive Streamlit dashboard
- Exports a professional investment summary as PDF

---

## 📊 Macroeconomic Indicators Used (from FRED)

| Indicator                    | FRED Code   | Insight Provided                                 |
|-----------------------------|-------------|--------------------------------------------------|
| Consumer Price Index (CPI)  | CPIAUCSL    | Measures inflation & purchasing power            |
| 10-Year Treasury Yield      | GS10        | Reflects interest rate environment               |
| Unemployment Rate           | UNRATE      | Indicates labor market health                    |
| Real GDP                    | GDPC1       | Represents overall economic performance          |

📌 All data sourced from: [https://fred.stlouisfed.org](https://fred.stlouisfed.org)

---

## 📁 Project Folder Structure

```
dynamic-portfolio-rebalancer/
├── data/
│   ├── raw/                
│   └── processed/            
├── notebooks/                
├── src/
│   ├── data_loader.py        
│   ├── portfolio_logic.py    
│   └── report_generator.py  
├── dashboard/
│   └── app.py                
├── reports/                  
├── README.md
├── requirements.txt
└── run_pipeline.py           
```

---

## 🛠️ Tools & Technologies Used

| Purpose            | Tool / Library            |
|--------------------|---------------------------|
| Data Source        | FRED (manual CSV download)|
| Programming        | Python (pandas, numpy)    |
| Dashboard          | Streamlit                 |
| Reporting          | ReportLab or WeasyPrint   |
| Data Visualization | matplotlib, seaborn       |

---

## 🚀 Getting Started

1. Clone the repository  
  
   ```

2. Install dependencies  
   
   ```

3. Launch the dashboard  
   
   ```

---

## 🧪 Sample Output (JSON)

```json
{
  "investor_profile": {
    "age": 25,
    "capital": 300000,
    "risk_tolerance": "Moderate"
  },
  "macro_score": {
    "Inflation": "High",
    "Bond_Yield": "Rising",
    "Unemployment": "Moderate",
    "GDP": "Stable"
  },
  "recommended_allocation": {
    "Equity": "40%",
    "Debt": "35%",
    "Gold": "20%",
    "Cash": "5%"
  },
  "rebalance_suggestion": true
}
```

---

## 📄 Report Preview

A sample investor report with justifications and rebalancing strategy is available in the `  ` folder.

---

## 🏆 Why This Project Matters

- 📈 Combines real-world economic data with investor profiling
- 🎓 Built fully from scratch to showcase my data + finance skills
- 🧠 Rule-based logic ensures transparency and interpretability
- 💼 Great fit for roles in **investment management**, **wealthtech**, and **financial data science**

---

## 👩‍💻 Author

**Devika Janardhanan**  
B.Tech CSE (Data Analytics) @ VIT-AP  
📬 devikajanardhanan214@gmail.com  
🔗 https://www.linkedin.com/in/devika-janardhanan-0421s?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BbOSOocErSyOUAWoKl19ong%3D%3D

---

## 📘 License

This project is open-source and available under the MIT License.
