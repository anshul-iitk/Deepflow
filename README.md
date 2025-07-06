
# Deepflow

## 1. Market Sentiment & Trader Performance Analysis mini Assignment

This task explores the relationship between **Bitcoin market sentiment (Fear/Greed)** and **trader performance** using real execution data.

### Dataset Sources
- `historical_data.csv` – Trader execution data from Hyperliquid  
- `fear_greed_index.csv` – Bitcoin sentiment index

### Key Findings
- Traders performed better on **Greed days**, especially with large trades.
- **SELL trades** consistently had higher win rates, especially during Fear.
- **BUY trades** showed higher profit under Fear sentiment; **SELL trades** did better under Greed.
- Greed days showed higher **PnL volatility** — indicating more aggressive risk behavior.

### Tools Used
- **Python** – Primary language for analysis  
- **Pandas** – Data loading, cleaning, and manipulation  
- **Matplotlib** – Plotting and visualizing PnL distributions and trends  
- **Seaborn** – Enhanced statistical data visualizations  
- **Jupyter Notebook** – Interactive analysis and reporting  

---

## 2. Bulldozer Price Prediction

Used historical auction data to build a model predicting bulldozer sale prices.

### Key Steps:
- Cleaned and preprocessed auction data (handled missing values, fixed data types).
- Parsed `saledate` to extract features like year, month, and day.
- Encoded categorical features.
- Trained a **Random Forest Regressor** for price prediction.
- Achieved a validation **RMSLE of 0.2154**.
- Generated predictions for the test set in the required format.

### Files:
- `bulldozer_prediction.ipynb` – Full notebook with preprocessing, training, and evaluation  
- `test_predictions.csv` – Final predictions on the test data  

### Tools & Technologies Used
- **Languages**: Python  
- **Libraries**: pandas, numpy, matplotlib, scikit-learn  
- **Platform**: Jupyter Notebook 
- **Version Control**: Git & GitHub  

---

##  Notes
These projects were part of my hands-on learning journey into data science and machine learning.  
All work is original, and I focused on applying practical techniques to real-world datasets.
