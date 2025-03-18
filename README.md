# Climate Change and Fuel Costs Analysis

## Overview  
Climate change and energy consumption are closely linked, with fuel costs playing a major role in both economic and environmental sustainability. This analysis explores fuel cost trends and statistics using data from the **Federal Energy Regulatory Commission (FERC)**, sourced from [this dataset](https://raw.githubusercontent.com/WalePhenomenon/climate_change/master/fuel_ferc1.csv).  

By analyzing key fuel-related metrics, we aim to uncover patterns in fuel pricing, consumption, and energy efficiency, ultimately highlighting the financial and environmental implications of fuel usage.

---

## Key Questions Answered  

### 1. **Which fuel type has the lowest average fuel cost per unit burned?**  
Energy costs vary by fuel type. This analysis identifies the fuel type with the **lowest average cost per unit burned**, shedding light on the most cost-effective energy source.

### 2. **Standard Deviation and 75th Percentile of Energy per Unit (Fuel_mmbtu_per_unit)?**  
The standard deviation helps us understand the variability in energy content across different fuels, while the 75th percentile indicates the upper range of fuel efficiency.

### 3. **Skewness and Kurtosis of Fuel Quantity Burned?**  
- **Skewness** measures whether fuel consumption data is **symmetrically distributed** or leans toward higher or lower values.  
- **Kurtosis** evaluates whether the data has **heavy or light tails**, indicating extreme variations in fuel consumption.

### 4. **Features with the Second and Third Lowest Correlation to Fuel Cost Per Unit Burned?**  
Understanding the correlation between fuel cost and other factors can reveal **which features have minimal impact** on pricing, helping refine energy pricing models.

### 5. **Percentage Change in Coal Fuel Cost Per Unit Burned (1998 vs. 1994)?**  
Tracking coal prices over time provides insights into cost fluctuations and economic trends, particularly regarding fossil fuel dependency.

### 6. **Which Year Had the Highest Average Fuel Cost Per Unit Delivered?**  
Identifying the most expensive year for fuel delivery highlights periods of economic strain, potentially linked to global energy crises or policy changes.

---

## Why This Analysis Matters  
- **Climate Change Impact**: Fuel consumption directly contributes to greenhouse gas emissions. Analyzing fuel efficiency and cost trends can support policies promoting cleaner energy.  
- **Economic Insights**: Understanding fuel cost trends helps industries, policymakers, and consumers make **informed financial decisions** regarding energy consumption.  
- **Data-Driven Decision Making**: By applying statistical analysis, we derive actionable insights that can help transition to **sustainable energy solutions**.  

### 🛠️ Tools & Methods  
This analysis was conducted using Python, leveraging **pandas, NumPy, and SciPy** for data processing and statistical analysis.

---

