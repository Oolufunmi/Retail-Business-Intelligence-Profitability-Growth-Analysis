# Retail-Business-Intelligence-Profitability-Growth-Analysis
This project analyzes 10,000+ rows of retail data to identify growth opportunities and operational inefficiencies. Moving beyond basic sales tracking, this analysis focuses on profitability margins and customer behavior to provide actionable recommendations for a mid-sized retail business.
# 📊 Retail Strategy & Profitability Analysis (2026)

## 🎯 Executive Summary
This project analyzes a dataset of **10,000+ retail transactions** to solve a specific business problem: **Identifying why high sales volume in certain categories is leading to profit loss.** Through this analysis, I discovered that the "Furniture" category is currently a "loss leader" due to inefficient shipping and discounting strategies, and I provided data-backed recommendations to recover 15% of lost margins.

---

## 🔗 Live Interactive Dashboard
👉 **[CLICK HERE TO VIEW THE INTERACTIVE REPORT](INSERT_YOUR_NOVYPRO_OR_POWERBI_LINK_HERE)**

---

## 🛠️ The Tech Stack
* **Power BI:** Data Modeling & Visualization.
* **Power Query:** ETL (Extraction, Transformation, Loading).
* **DAX:** Advanced statistical and financial modeling.
* **PowerPoint:** Executive storytelling and stakeholder reporting.

---

## 🔍 The "Quantity vs. Profit" Deep Dive
**Business Question:** "Should we incentivize bulk orders to increase profit?"

I used a **Scatter Plot with a Trend Line** to test the correlation between order quantity and net profit.



**The Verdict:** The correlation is **Weak/Negative** for certain categories. Increasing order quantity without adjusting shipping surcharges for "Overweight" items (like Tables) actually reduces our net profit. 

**Recommendation:** Implement a tiered shipping cost structure for orders exceeding 5 units in the Furniture category.

---

## 💡 Technical Showcase: DAX & Modeling
I focused on high-performance DAX measures to ensure the dashboard remains fast and accurate:

* **Profit Margin %:**
    ```dax
    Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
    ```
* **Total Orders (Unique):**
    ```dax
    Total Orders = DISTINCTCOUNT('SalesData'[Order ID])
    ```

---

## 📈 Visualizing Growth (PowerPoint Slides)
I translated the data into a boardroom-ready presentation. Below are the key strategic slides:



---

## 📂 Project Structure
* `Analysis_Dashboard.pbix` - The core Power BI file.
* `Retail_Presentation.pptx` - Stakeholder summary slides.
* `Data_Source.csv` - The raw transaction data.

---

## 👋 Connect with me
* **LinkedIn:** [Insert Link]
* **Portfolio:** [Insert Link]
* **Email:** [Insert Email]
