# P&G Product Strategy – Data Science Business Case

This project is based on a **business case by P&G** where the goal was to recommend **data-driven product strategy** using multi-source datasets (COVID-19 data, ESG metrics, and stock data).  

---

## 📌 Problem Statement
P&G wanted to understand:
1. Whether external factors like **COVID-19** cases influenced its **stock performance**.  
2. The role of **ESG (Environmental, Social, Governance) metrics** in consumer perception and demand.  
3. How data insights can **guide product and sustainability strategy**.

---

## 🔍 Data Sources
- **COVID-19 Cases Data** – worldwide daily case counts  
- **P&G Stock Data** – 2017–2025, daily adjusted closing price  
- **ESG Metrics** – CO₂ emissions, water usage, and plastic usage  

---

## 🛠️ Methodology
- **Data Cleaning & Integration** – prepared time-series datasets for alignment.  
- **Correlation Analysis** – Pearson & Spearman correlation to test COVID cases vs. stock prices.  
- **Trend Analysis** – ESG metrics over multiple years vs. consumer outcomes.  
- **Gap Identification** – checked granularity of ESG data (global vs. regional vs. product level).  

---

## 📊 Key Insights
- **COVID-19 vs. Stock**: No significant correlation → P&G stock showed **resilience** to pandemic shocks.  
- **ESG Metrics vs. Demand**: No clear negative impact of higher ESG costs → ESG is **neutral-to-positive** for consumer perception.  
- **Data Gaps**: ESG data lacked product-level or region-level granularity, limiting precision.  

---

## 💡 Recommendations
- **Continue ESG Initiatives** – consumers show no negative reaction; supports brand sustainability.  
- **Improve ESG Data Granularity** – track metrics by **region/product** for actionable insights.  
- **Enhance Supply-Chain Resilience** – COVID showed resilience, but proactive monitoring is needed.  
- **Real-Time Feedback Loops** – integrate product feedback analytics to guide agile strategy.  

---

## 🧰 Tools & Techniques
- Python (Pandas, NumPy)  
- Statistical Analysis (Pearson, Spearman)  
- Data Visualization (Matplotlib, Seaborn, Power BI)  

---

## 📂 Repository Structure
