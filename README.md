# **Time Series Analysis of Civil Conflict: Africa (ARIMA Modeling)**  

![Language](https://img.shields.io/badge/language-Python-blue.svg)
![Status](https://img.shields.io/badge/status-complete-blue.svg)
![License](https://img.shields.io/badge/license-academic-green.svg)

## **Overview**  
This repository documents an exploratory project in applying **time series analysis** to civil conflict event data in Africa. The goal was to investigate whether historical patterns in conflict data alone could be used to predict future events, using **Box-Jenkins ARIMA modeling**.  

The analysis focused on four African countries experiencing civil conflict, with a **full end-to-end modeling process demonstrated for Ethiopia and Somalia**.  

### **Key Insights**  
- Out-of-sample forecasting performance varied by country:
  - **Somalia:** ARIMA(3,1,0) performed well with low RMSE values.  
  - **Ethiopia:** ARIMA(1,1,1) was the best fit but less effective in forecasting.  
- Results demonstrate that **simple ARIMA models can deliver strong forecasting accuracy** even when relying solely on past events, though predictive performance is highly country-dependent.  

---

## **Repository Structure**  

```
├── data/
│ ├── Ethiopia.csv
│ └── Somalia.csv
│
├── notebooks/
│ └── africa-time-series.ipynb
│
└── output/
└── IST 341_Final Presentation_Zhamilia Klycheva(Jama).pdf
```

- **data/** – Monthly time series event counts for Ethiopia and Somalia (subset of ACLED conflict event data).  
- **notebooks/** – Jupyter Notebook implementing data cleaning, exploratory data analysis (EDA), and ARIMA modeling.  
- **output/** – Final project presentation summarizing results and methodology.  

---

## **Data & Methodology**  
- **Data source:** Armed Conflict Location Event Data Project (ACLED).  
- Each country’s data was grouped at a **monthly frequency**, removing non-violent events.  
- The **Box-Jenkins ARIMA approach** was applied:
  1. Model identification (ACF/PACF plots, differencing)  
  2. Parameter estimation and evaluation using AIC/BIC  
  3. Diagnostic checks and rolling forecast evaluation  

---

## **Future Extensions**  
- Extend analysis beyond univariate ARIMA by exploring:
  - **Cointegration models:** Test long-term equilibrium relationships between conflict series across countries.  
  - **ARIMAX models:** Include exogenous variables (e.g., socio-economic or political factors) to improve explanatory power.  
- Expand full analysis to all four African countries studied during the EDA phase.  

---

## **Notes**  
- This was a **school project** for a time series analysis class (IST 341) and is provided for **academic reference only**.  
- The repository is marked as **complete** and will not be updated.  

---

## **License**  
This project is available for academic and educational purposes only.  


