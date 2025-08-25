# CDS Prediction from Company Fundamentals

## Overview  
This project explores the prediction of **Credit Default Swap (CDS) spreads** using a company’s fundamental financial data.  
By leveraging balance sheets, income statements, and cashflow statements, the aim is to be able to derive the **implied CDS spread** via a **hazard rate model**.  

The motivation is to provide a data-driven framework for assessing credit risk, offering insights beyond traditional ratings-based approaches.  

## Key Features  
- **Data Sources**: Financial statements (Balance Sheet, Income Statement, Cashflow).  
- **Model**: Hazard rate model for default probability and implied CDS spread.  
- **Objective**: Estimate credit risk directly from fundamentals without relying on market-quoted CDS.  

## Tech Stack  
- **Python** (pandas, numpy, scikit-learn, statsmodels)  
- **Jupyter Notebooks** for model development and testing  
- **Matplotlib / Seaborn** for visualization  

## Roadmap  
1. Data preprocessing & feature engineering from fundamentals.  
2. Implement hazard rate model for default intensity estimation.  
3. Calibrate model against observed CDS data (where available).  
4. Evaluate accuracy and robustness of implied spread predictions.  

## Applications  
- Credit risk management  
- Alternative credit scoring models  
- Stress testing & scenario analysis  

---

🚀 Contributions and feedback are welcome!  
