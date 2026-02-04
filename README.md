# Retail-Business-Intelligence-Profitability-Growth-Analysis
This project analyzes 10,000+ rows of retail data to identify growth opportunities and operational inefficiencies. Moving beyond basic sales tracking, this analysis focuses on profitability margins and customer behavior to provide actionable recommendations for a mid-sized retail business.
## 🎯 Executive Summary
This project analyzes a dataset of **10,000+ retail transactions** to solve a specific business problem: **Identifying why high sales volume in certain categories is leading to profit loss.** Through this analysis, I discovered that the "Furniture" category is currently a "loss leader" due to inefficient shipping and discounting strategies, and I provided data-backed recommendations to recover 15% of lost margins.

---

## 🔗 Live Interactive Dashboard
👉 **[CLICK HERE TO VIEW THE INTERACTIVE REPORT](https://app.powerbi.com/groups/me/reports/f94bf851-325e-49c0-b014-1c5db49a7ffd/07d39cc8090006a020b2?experience=power-bi)**
<img width="572" height="317" alt="image (12)" src="https://github.com/user-attachments/assets/902da999-d8c6-45ae-affd-88d53b079345" />
<img width="569" height="362" alt="image (13)" src="https://github.com/user-attachments/assets/367e4371-ace7-45b6-99aa-84d7377ae93e" />
<img width="567" height="316" alt="image (14)" src="https://github.com/user-attachments/assets/7b7d5fbe-fae0-49fa-a63c-3b5318de5899" />
<img width="557" height="318" alt="image (15)" src="https://github.com/user-attachments/assets/29ea4c61-c0ab-4ecd-a295-6f0e5c5c14e4" />





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
* **LinkedIn:** [https://www.linkedin.com/in/olufunmilolaolaewe]
* **Portfolio:** [https://github.com/Oolufunmi]
* **Email:** [olufunmilolaolapejuolaewe@gmail.com]
