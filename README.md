# 📊 Global Superstore Sales Analysis & 7-Day Forecast

**Business Intelligence | Time Series Forecasting | 2015–2018 Historical Analysis**

This project delivers a full end-to-end analysis of the Global Superstore dataset, covering historical sales trends, regional performance, product category insights, customer segmentation, and a dual-model forecasting approach (Prophet & SARIMA) for short-term operational planning.

The report is designed to support executive decision-making, inventory optimization, and risk management across key business units.

---

## 🚀 Executive Summary

The analysis reveals a strong upward sales trajectory from 2016–2018, driven primarily by Technology products and the Consumer market segment. A 7-day forecast built using **Prophet** and **SARIMA** provides a reliable planning range of **2,000–2,900 daily units sold**.

### **Key Insights**

* **50% growth** in total sales from 2016 to 2018
* **West & East** regions generate **55.7%** of total revenue
* **Technology** is the top category with **$830K+** revenue
* **Phones, Chairs, and Storage** lead sub-category performance
* Forecast models show strong seasonality and weekly patterns

### **Strategic Recommendations**

* Maintain inventory for **2,000–2,900 units/day**
* Expand into underperforming **Central & South** regions
* Prioritize **Technology & Furniture** categories
* Prepare early for strong **Q4 seasonal spikes**

---

---

## 📘 Dataset Overview

| Attribute             | Summary                                       |
| --------------------- | --------------------------------------------- |
| **Records**           | 9,800 transactions                            |
| **Time Span**         | 2015–2018                                     |
| **Data Quality**      | 99.9% complete (only 11 missing postal codes) |
| **Categories**        | 3 main categories, 17 sub-categories          |
| **Geographic Spread** | 4 U.S. regions                                |

### **Preprocessing Actions**

* Standardized date fields for time-series modeling
* Imputed missing postal codes (e.g., Burlington, Vermont)
* Removed redundant identifiers (Row ID)
* Achieved **100% clean dataset** for modeling

---

## 📈 Historical Sales Performance (2015–2018)

### **Trend Summary**

* **2015–2016**: Minor decline (approx. -2% to -4%)
* **2016–2017**: Strong recovery (+30%)
* **2017–2018**: Continued growth (+20%)

**Key Observations**

* Strong Q4 seasonality
* Daily volatility from near-zero to $25K+
* Overall upward momentum post-2016

---

## 🌍 Regional Analysis

| Region  | Sales | Market Share | Rating |
| ------- | ----- | ------------ | ------ |
| West    | $708K | 28.5%        | ⭐⭐⭐⭐⭐  |
| East    | $678K | 27.2%        | ⭐⭐⭐⭐⭐  |
| Central | $501K | 20.1%        | ⭐⭐⭐    |
| South   | $391K | 15.7%        | ⭐⭐     |

**Insight:** West & East dominate, but Central & South present major growth opportunities.

---

## 🛒 Product Category Performance

### **Revenue Breakdown**

* **Technology — $830K (33.4%)**
* **Furniture — $741K (29.8%)**
* **Office Supplies — $719K (28.9%)**

### **Top Sub-Categories**

* **Phones — $330K+**
* **Chairs — $328K+**
* **Storage — $223K+**

**Opportunity:** Evaluate discontinuing low-movers (Art, Envelopes, Fasteners).

---

## 👥 Customer Segment Insights

| Segment     | Revenue | Share | Growth Potential |
| ----------- | ------- | ----- | ---------------- |
| Consumer    | $1.16M  | 46.7% | High             |
| Corporate   | $706K   | 28.4% | Medium           |
| Home Office | $429K   | 17.3% | High             |

**Insight:** Strong B2C performance, with room to expand B2B and home office segments.

---

## 🔮 7-Day Forecasting Models

Two models were used to strengthen reliability:

### **1. Prophet (Facebook)**

* Avg daily forecast: **2,002 units**
* Range: **1,306 – 2,556**
* Conservative, trend-focused
* Great for seasonality + outlier handling

### **2. SARIMA**

* Avg daily forecast: **2,908 units**
* Range: **2,798 – 3,130**
* Highly responsive to weekly patterns
* Model: `ARIMA(0,1,1) × (1,0,0)[7]`

### **Forecast Comparison**

* SARIMA consistently predicts **15–114% higher** than Prophet
* Both models detect strong weekly seasonality
* A hybrid (ensemble) approach is recommended

---

## ⚠️ Risk & Uncertainty Assessment

### **Major Drivers of Volatility**

* Seasonal Q4 spikes
* Large corporate orders
* Regional sales disparities
* Natural high daily variance

### **Mitigation Strategies**

* Maintain **20–30% safety stock**
* Track forecast vs actual daily
* Run conservative, moderate, and optimistic scenarios
* Strengthen supply chain flexibility

---

## 📌 Strategic Recommendations

### **1. Inventory Planning**

* Prophet baseline: **~2,000 units/day**
* SARIMA peak: **~2,900 units/day**
* Hybrid forecast: **2,400–2,600 units/day** recommended

### **2. Regional Strategy**

* Expand in **Central & South**
* Sustain West/East momentum

### **3. Product Strategy**

* Prioritize Phones, Chairs, Storage
* Review low-margin categories

### **4. Risk Management**

* Build Q4 stock early
* Monitor major B2B orders
* Prepare for volatility swings

---

## 💰 Financial Impact Analysis

| Scenario               | Expected Revenue |
| ---------------------- | ---------------- |
| Conservative (Prophet) | ~$14,000/day     |
| Optimistic (SARIMA)    | ~$20,000/day     |

**Stockout Risk:** ~$6,000/day lost potential
**ROI Opportunity:** 15–20% revenue lift with correct inventory positioning
**Payback Period:** 3–4 months

---

## 🧾 Conclusion

The analysis demonstrates:

* Strong business health
* Clear seasonal patterns
* Valuable growth opportunities
* Reliable dual-model forecasting

A structured, data-driven strategic plan can significantly enhance revenue, reduce stockouts, and optimize operational performance.

---

## 🛠️ Technical Appendix

### **Models Used**

* Prophet: Additive seasonality, trend modeling
* SARIMA: `(0,1,1) × (1,0,0)[7]` weekly seasonality
* 4 years of historical data for robust training

### **Assumptions**

* No major market disruptions
* Seasonal patterns remain consistent
* Forecast horizon limited to 7 days for maximum accuracy

---

## 👤 Author

**Analyst:** *Patrick Mwangi Gichuki*
**Portfolio:** [https://gichuki.site](https://gichuki.site)
**LinkedIn:** [https://www.linkedin.com/in/patrick-gichuki-the-bi-analyst](https://www.linkedin.com/in/patrick-gichuki-the-bi-analyst)

