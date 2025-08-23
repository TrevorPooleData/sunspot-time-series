# 🌞 Sunspot Time Series Analysis (1700–2024)


## Introduction

Sunspot observations have been systematically recorded since 1700, forming one of the longest continuous datasets in astronomy (Arlt and Vaquero, 2020). These records are crucial for understanding long-term solar activity and its potential influence on Earth’s climate and space weather. The Royal Observatory of Belgium, through its Solar Influences Data Analysis Center (SIDC), has played a central role in compiling and maintaining the International Sunspot Number series. In 2015, this series underwent a major revision with the release of Version 2.0, which corrected historical inconsistencies and improved the homogeneity of the data (Clette and Lefèvre, 2015). The updated series incorporates recalibrated values based on a broader network of observing stations and refined methodologies, offering a more accurate representation of solar activity over time. These improvements enhance the reliability of long-term analyses and forecasting models that depend on historical sunspot data.

---

## 📌 Research Question

**“How can historical sunspot data from 1700 to 2024 be explored and visualised to assess data quality, and how can a model be developed to forecast sunspot activity from 2025 to 2050?**

---

## 📁 Project Structure

```
sunspot-time-series/
├── deliverables/
│   ├── Sunspot_Analysis_Report.docx # Final written report
│   └── sunspot_analysis.ipynb       # Jupyter Notebook with full analysis
├── data/
│   └── SN_y_tot_V2.0.csv            # Raw dataset from SILSO (not included if too large)
└── README.md                        # Project overview
```

---

## 🧪 Methods
Data Source:
International Sunspot Number V2.0 from the **Royal Observatory of Belgium, Solar Influences Data Analysis Center (SILSO)**  
DOI: 10.24414/qnza-ac80  
Access: https://www.sidc.be/SILSO

Tools Used:
- Python (pandas, numpy, matplotlib, statsmodels, pmdarmima)

Techniques:
- Reading data from CSV file
- Data recoding
- Data quality checking and visialisation
- Calculation of confidence intervals
- Time series analysis
- Forecasting model (SARIMA)
- Evaluation metrics (RMSE, MAE, AIC)
- Forecast visualisation

---

## 📊 Deliverables

- 📄 Final Report (Word)
- 🧪 Jupyter Notebook

---

## 📚 References
- Arlt, R. and Vaquero, J.M., 2020. *Historical sunspot records*. Living Reviews in Solar Physics, 17(1). Available at: [https://link.springer.com/article/10.1007/s41116-020-0023-y](https://link.springer.com/article/10.1007/s41116-020-0023-y) [Accessed 23 Aug. 2025].
- Clette, F. and Lefèvre, L., 2015. *SILSO Sunspot Number V2.0*. World Data Center SILSO, Royal Observatory of Belgium. Available at: https://doi.org/10.24414/qnza-ac80 [Accessed 23 Aug. 2025].
- Clette, F., Lefèvre, L., Cagnotti, M., Cortesi, S. and Bulling, A., 2016. The revised sunspot number: assembling all corrections. Solar Physics, 291(9-10), pp.2629–2651.
- Hathaway, D. H. (2015). The Solar Cycle. Living Reviews in Solar Physics, 12, Article 4. https://doi.org/10.1007/lrsp-2015-4

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
