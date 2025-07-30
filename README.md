# DSPP-Summative-DS-Project
Data Science Project for BPP Date Science Professional Practice Summative Assessment

# 🌞 Sunspot Time Series Analysis (1749–2025)

This project explores long-term solar activity using monthly sunspot data from the SILSO network. It applies time series analysis and forecasting techniques to investigate cyclical solar patterns and assess how data quality affects model performance.

---

## 📌 Research Question

**How accurately can long-term sunspot activity be forecasted using historical data from 1749 to 2025, and what impact do data quality and observational inconsistencies have on model performance?**

---

## 📁 Project Structure

```
sunspot-time-series/
├── notebooks/
│   └── sunspot_analysis.ipynb       # Jupyter Notebook with full analysis
├── deliverables/
│   ├── Sunspot_Analysis_Report.docx # Final written report
│   └── Sunspot_Dashboard.twbx       # Tableau workbook for interactive visualisation
├── data/
│   └── sunspot_data.csv             # Raw dataset from SILSO (not included if too large)
└── README.md                        # Project overview
```

---

## 🧪 Methods
Data Source:
International Sunspot Number V2.0 from the **Royal Observatory of Belgium, Solar Influences Data Analysis Center (SILSO)**
DOI: 10.24414/qnza-ac80
Access: https://www.sidc.be/SILSO

Tools Used:
- Python (pandas, statsmodels, matplotlib)
- Tableau

Techniques:
- Time series decomposition
- Forecasting models (ARIMA, Prophet)
- Evaluation metrics (RMSE, MAE)
- Data quality visualisation

---

## 📊 Deliverables

- 📄 Final Report (Word)
- 📈 [Tableau Dashboard](deliverables/Sunspot_Dashboard.twbx)
- 🧪 Jupyter Notebook

---

## 📚 Key Reference
Hathaway, D. H. (2015). The Solar Cycle. Living Reviews in Solar Physics, 12, Article 4. https://doi.org/10.1007/lrsp-2015-4

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/sunspot-time-series.git
   cd sunspot-time-series

---

## 📌 License
This project is for academic and educational purposes.

---

## 🙋‍♂️ Author
Trevor Poole
