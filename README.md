# 📊 Analysis & Visualization of P&L Data in Excel  
**Organizing, Visualizing, and Analyzing Financial Information Downloaded from Bloomberg**

Financial data from Bloomberg terminals is rich and valuable but it rarely comes ready for decision-making. This project showcases how I transformed raw, unformatted Bloomberg exports into a clean, interactive Profit &amp; Loss (P&amp;L) analysis using Excel.

![Excel](https://img.shields.io/badge/Tool-Microsoft%20Excel-green?logo=microsoft-excel&logoColor=white)
![Project Type](https://img.shields.io/badge/Type-Financial%20Analysis-blue)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Years Covered](https://img.shields.io/badge/Years-2016--2023-lightgrey)

---

## 🧭 Project Overview
This project demonstrates how to **transform raw Bloomberg financial data** into a clean, analytical, and presentation-ready **Profit & Loss (P&L) analysis in Excel**.

Using Adidas (Ticker: *ADS GY Equity*) as the focus, the project showcases how advanced Excel functions, formatting, and visualization techniques can convert complex datasets into **actionable business insights**.

---

## 🎯 Objectives
- Structure and format Bloomberg-exported financial data into a concise, professional P&L.  
- Calculate **key financial metrics** such as Gross Profit Margin, EBIT Margin, and Revenue CAGR.  
- Visualize growth and profitability trends with clear, management-friendly charts.  
- Interpret results and communicate findings through a one-page executive summary.

---

## 🧩 Dataset
**Source:** Bloomberg Terminal Extraction  
**Company:** Adidas AG (ADS GY Equity)  
**Period:** FY 2016–2023 (Focus: FY 2019–2023)  
**Key Metrics:**
- Revenue, Cost of Sales, Operating Expenses, Gross Profit, EBIT, EPS  
- Segmentation by Product, Brand, and Geography  

---

## ⚙️ Project Tasks

### **Task 1: Create P&L Structure and Apply Formatting**
- Built a clean, professional **P&L table** with proper alignment and accounting number formatting.  
- Included key line items:  
  `Revenue → Cost of Sales → Gross Profit → Operating Expenses → EBIT`  
- Applied **conditional formatting** for clarity and visual separation.

### **Task 2: Lookup Source Data, Calculate Margins & Growth Rates**
- Populated P&L automatically using **nested lookup functions** (`SUMIFS`, `XLOOKUP`).  
- Calculated:
  - **Gross Profit Margin = Gross Profit / Revenue**  
  - **EBIT Margin = EBIT / Revenue**  
  - **Revenue CAGR (2019–2023)** using formula:  
    ```excel
    =(F2/B2)^(1/(2023-2019))-1
    ```

### **Task 3: Create Visualization**
- Built a **combo chart**:  
  - *Bars* = Revenue  
  - *Line* = EBIT Margin (%)  
- Designed for management to instantly grasp revenue trajectory and profitability improvements.

### **Task 4: Interpret the Data**
- Compared Adidas’ P&L between 2019 and 2023 to identify growth and efficiency trends.  
- Summarized insights in an **executive summary sheet** and `reports/` folder.

---

## 📈 Key Findings & Insights

| Metric | 2019 | 2023 | Change / CAGR |
|:--|:--:|:--:|:--:|
| **Revenue CAGR** | — | — | **7.33%** |
| **Retail Segment CAGR** | — | — | **14.49%** |
| **Wholesale Segment CAGR** | — | — | **4.82%** |
| **Gross Profit Margin** | 46% | 50% | ↑ +4 pts |
| **EBIT Margin** | 5% | 9% | ↑ +4 pts / **22.79% CAGR** |

---

## 💡 Insights Summary
- **Strong growth momentum:** Revenue increased consistently, led by the Retail segment.  
- **Profitability improvement:** Gross and EBIT margins expanded, reflecting cost efficiency and pricing control.  
- **Operational excellence:** EBIT grew at ~22.8% CAGR, signaling optimized operations.  
- **Balanced strategy:** Sustainable growth achieved through a healthy mix of top-line and margin expansion.

---

## 🧠 Tools & Techniques Used
| Category | Details |
|-----------|----------|
| **Spreadsheet Tool** | Microsoft Excel |
| **Functions Used** | SUMIFS, XLOOKUP, CAGR formula, Percentage Calculations |
| **Formatting** | Accounting Number Style, Conditional Formatting, Named Ranges |
| **Visualization** | Combo Chart (Revenue vs. EBIT Margin), Data Bars |
| **Automation** | Optional VBA Macro for chart export and workbook refresh |
| **Analysis Skills** | Financial Trend Analysis, Margin Evaluation, Profitability Insights |  

---

## 🧾 Executive Summary (Highlights)
- Revenue CAGR (2019–2023): **7.33%**  
- Retail Segment CAGR: **14.49%**  
- Gross Profit Margin: **46% → 50%**  
- EBIT Margin: **5% → 9%**  
- Conclusion: Adidas maintained robust growth while expanding profitability — demonstrating disciplined cost control, effective pricing strategy, and operational efficiency.

---

## 🔒 License & Privacy Notice 
This project uses publicly available Bloomberg data for educational purposes only.  
No proprietary or confidential company information is shared.

---

## 🏁 Project Status
✅ Completed — available for review and portfolio showcase  
📅 Period: FY 2019–2023  
👤 Analyst: *Nishi*  

---

## 🧠 Learnings
- Excel can rival BI tools in financial analytics when structured properly.  
- Clean design and storytelling elevate technical work to business value.  
- Consistency, automation, and readability make analyses repeatable and professional.

---

### ⭐ If you found this project interesting  
Give it a ⭐ on GitHub and connect with me on [LinkedIn](#) to discuss financial analytics and Excel automation!

---

© 2025 Nishi — All rights reserved.

