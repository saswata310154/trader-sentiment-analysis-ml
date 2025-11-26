# Trader Behavior vs Market Sentiment Analysis

### ML · Statistical Analysis · EDA · Crypto Sentiment Intelligence

This project analyzes how trader behavior (profit, risk, volume, and trade timing) aligns or diverges from overall crypto market sentiment (Fear to Greed). Using **EDA**, **statistical testing**, and **machine learning models** (Random Forest & XGBoost), the study uncovers hidden behavioral patterns and predictive signals that improve trading strategy decisions.


##  Project Objectives

* Analyze how trader actions change across **sentiment states** (Fear → Greed).
* Identify behavioral signals in:

  * Profitability
  * Risk-taking
  * Trade value
  * Win/Loss patterns
  * Time-based trading behavior
* Build ML models to predict trade outcomes and extract feature importance.
* Validate findings with statistical tests (Chi-square, t-test, correlation).


##  Methodology Overview

### **1. Data Preparation**

* Loaded Hyperliquid trader data + Bitcoin sentiment data
* Cleaned timestamps, numeric values, missing fields
* Merged datasets into a unified dataset

### **2. Feature Engineering**

* TradeValue
* ProfitPerValue
* SentimentEncoded
* IsBuy
* Hour, DayOfWeek
* Profit-risk interactions

### **3. Behavioral EDA**

* Profit comparison across sentiment groups
* Win rate analysis
* Volume analysis
* Time-of-day trading patterns
* Correlation heatmap

### **4. Statistical Tests**

* Chi-square test (Sentiment × Win/Loss)
* t-tests (Profit & Trade Value differences)

### **5. Machine Learning**

* Random Forest & XGBoost in parallel
* Feature importance extraction
* ROC-AUC evaluation
* Full confusion matrix analysis

---

##  Key Insights

* **Greed phases** lead to higher profitability and increased win probability
* **Extreme Fear** triggers unusually high-volume trades, indicating panic reactions
* Time of day significantly affects win rates
* ML models achieved near-perfect ROC-AUC = **1.00**
* Sentiment, ProfitPerValue, and TradeValue were strong predictors

---

## How to Run

1. Open **notebook_1.ipynb** in **Google Colab**
2. Upload CSV files into `csv_files/` if needed
3. Run the notebook sequentially
4. Outputs will automatically be saved into `outputs/`
5. Final processed data saves to `csv_files/`

---

## Reports Included

### ** Final_Project_Report_Complete.docx**

A polished industry-style report including:

* Executive summary
* Full methodology
* EDA visuals
* Statistical findings
* ML evaluation
* Strategic recommendations

### ** ds_report.pdf**

Shorter summary version.

---

##  Contact

Created by **Saswata Sarkar**
M.Sc. Data Science | Machine Learning & Analytics
For collaboration: *saswata.ku2024@gamil.com*

---


