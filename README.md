#  US Treasury Yield Curve Analysis

A data-driven project that analyzes the US Treasury Yield Curve using Python and FRED (Federal Reserve Economic Data). This project focuses on understanding interest rate movements, yield curve structures, and their implications on the economy and financial markets.

---

##  Project Overview

The US Treasury Yield Curve is one of the most important indicators in finance. This project:

- Extracts historical yield data using the FRED API  
- Visualizes yield trends across different maturities  
- Analyzes yield curve shapes (Normal, Flat, Inverted)  
- Identifies patterns linked to economic cycles and market events  

---

## Key Features

- Data extraction from FRED API  
- Time-series visualization of yields  
- Pairplot and distribution analysis  
- Yield curve plotting for selected dates  
- Yield spread analysis (short-term vs long-term rates)  
- Detection of yield curve inversion  

---

##  Tech Stack

- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- fredapi (FRED API)  

---

## Project Structure

US-Treasury-Yield-Analysis/
│
├── US T-Yield.ipynb   # Main analysis notebook  
├── README.md          # Documentation  

---

##  Installation & Setup

### 1. Clone the Repository
git clone https://github.com/your-username/us-treasury-yield-analysis.git  
cd us-treasury-yield-analysis  

### 2. Install Dependencies
pip install pandas matplotlib seaborn fredapi  

### 3. Add FRED API Key

Get your API key from: https://fred.stlouisfed.org/

Add it in your code:

from fredapi import Fred  
fred = Fred(api_key='YOUR_API_KEY')  

---

##  Analysis Performed

### Yield Curve Visualization
Comparison of yields across maturities (short-term to long-term)

### Trend Analysis
Study of how interest rates evolve over time

### Yield Spread
Difference between long-term and short-term yields  
Important for predicting economic slowdowns  

### Curve Types
Normal Curve → Healthy economy  
Flat Curve → Transition phase  
Inverted Curve → Possible recession signal  

---

##  Key Insights

- Yield curve inversion is a strong recession indicator  
- Long-term vs short-term spread reflects market expectations  
- Historical patterns help in macroeconomic analysis  
- Interest rate trends impact equity and bond markets  

---

##  Sample Outputs

The notebook includes:
- Time series plots of treasury yields  
- Pairwise correlation plots  
- Distribution plots  
- Yield curve snapshots  

---

##  Data Source

Federal Reserve Economic Data (FRED)

---

## Use Cases

- Financial market analysis  
- Macroeconomic research  
- Investment decision support  
- Academic projects and learning  

---

## Contributing

Contributions are welcome. You can:
- Improve visualizations  
- Add predictive models  
- Enhance analysis with machine learning  

---

##  Contact

Ankit Singh  
Feel free to connect for collaboration or queries  

---

## ⭐ If you like this project

Give it a star on GitHub and share it with others.
