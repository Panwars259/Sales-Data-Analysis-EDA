# 📊 Sales Data Analysis using Python (EDA Project)

### 🧠 Project Overview  
This project explores a simulated **retail sales dataset** using Python to derive actionable business insights.  
It demonstrates skills in **data cleaning, feature engineering, EDA, and insight reporting** — covering the full analytical workflow from raw data to strategic interpretation.

---

## 🧩 1️⃣ Project Objectives
- Analyze sales performance across countries, products, and time.
- Identify top-performing items, customers, and warehouses.
- Understand discount effectiveness and customer retention.
- Support data-driven decision-making using business insights.

---

## 🛠️ 2️⃣ Tools & Libraries Used
- **Programming:** Python  
- **Libraries:** Pandas, Matplotlib, Seaborn  
- **Environment:** Google Colab 

---

## 🧹 3️⃣ Data Cleaning & Preprocessing
- Verified dataset integrity (no duplicates found) and converted relevant columns to correct data types (e.g., InvoiceDate → datetime, InvoiceNo → string, etc.).
- Handled missing values in numerical features (such as ShippingCost, WarehouseLocation, etc.).
- Created new derived columns such as:
  - `TotalPrice` → to measure total revenue  
  - `Year-Month` → for monthly sales trend analysis 
- Cleaned inconsistent entries and ensured accurate data formatting.
- Prepared the dataset for visual exploration and further analysis.

---

## 📈 4️⃣ Business Queries & KPIs Analyzed
The analysis answers several key business questions, such as:

| **#** | **Business Query** | **Purpose** |
|-------|--------------------|--------------|
| 1 | Overall Sales Performance | Understand total revenue and sales volume |
| 2 | Top 3 Best-Selling Products | Identify most profitable SKUs |
| 3 | Top 10 High-Value Customers | Find loyal and high-spending clients |
| 4 | Customer Retention Analysis | Measure repeat purchase rate |
| 5 | Average Order Value (AOV) | Evaluate spending behavior per order |
| 6 | Average Discount by Category | Assess pricing and promotional impact |
| 7 | Most Common Payment Method | Observe transaction preferences |
| 8 | Orders by Priority Level | Study operational workload |
| 9 | Top Performing Warehouses | Measure efficiency of logistics hubs |
| 10 | Peak Hour of Sales Activity | Identify optimal timing for promotions |
| 11 | Top Countries by Revenue | Discover high-performing markets |
| 12 | Product Return Analysis | Evaluate return rates and causes |

---

## 📊 5️⃣ Exploratory Data Visualizations
The following visual analyses were performed using **Matplotlib** and **Seaborn**:

1. **Sales by Country** — Compare global market performance  
2. **Sales by Category** — Identify strong product segments  
3. **Return by Country** — Observe geographical return patterns  
4. **Sales Over Time** — Track seasonal and monthly trends  
5. **Discount vs Price Levels** — Understand pricing patterns  
6. **Discount vs Sales (Regression)** — Assess relationship between discounts and revenue  
7. **Sales Distribution by Discount Levels** — Visualize optimal discount ranges  

---

## 💡 6️⃣ Key Insights Summary

### 🧾 Overall Performance
- Total revenue: **₹44.63 million** from **46K+ orders**  
- Average Order Value (AOV): **₹967.48**  
- Balanced international sales distribution  

### 🛍️ Product-Level Insights
- **Top products:** White Mug, USB Cable, Wall Clock  
- **Furniture & Accessories** outperform other categories slightly  
- Desk Lamp generates high revenue despite fewer units — higher margins  

### 🌍 Country-Level Insights
- **Top markets:** Belgium, UK, and USA  
- Return rate stable (~9–10%), lowest in Spain  
- Balanced international reach with consistent demand  

### 👥 Customer Behavior
- **77% one-time buyers**, **23% repeat buyers** → retention needs improvement  
- One guest customer (NaN ID) had highest purchase total — missed loyalty opportunity  

### 💳 Operational & Transactional
- **Bank Transfer** most used payment method  
- **Top warehouses:** Amsterdam, London, Rome, Berlin  
- 995 orders missing warehouse data → needs validation  

### ⏰ Temporal Trends
- Sales peak during **9–11 AM** and around **11 PM**  
- **Tuesday & Wednesday** show highest weekly sales  
- 2024 recorded best annual performance  

### 💸 Discount & Pricing Insights
- Optimal discount range: **14–22%** (high volume, stable profit)  
- Weak negative correlation (r = -0.22) between discount and sales  
- Deep discounts (>30%) show diminishing returns  

---

## 🧠 7️⃣ Summary of Key Takeaways

| **Aspect** | **Key Insight** |
|-------------|-----------------|
| **Total Revenue** | ₹44.63 M from 46 K+ orders |
| **Top Products** | White Mug, USB Cable, Wall Clock |
| **Repeat Customers** | 23 % retention — improvement needed |
| **Average Order Value** | ₹ 967.48 |
| **Top Countries** | Belgium, UK, USA |
| **Return Rate** | ~9.8 % (stable globally) |
| **Top Warehouses** | Amsterdam, London, Rome, Berlin |
| **Peak Sales Hour** | 9 AM |
| **Effective Discount Range** | 14–22 % |
| **Best Sales Days** | Tuesday & Wednesday |

---

## 💼 8️⃣ Final Business Interpretation
The analysis reveals a **financially strong, operationally balanced company** with:
- Consistent international performance  
- Diversified product portfolio  
- Efficient warehouse operations  
- Moderate but steady customer base  

**Opportunities for growth:**
- Boost customer retention via loyalty programs  
- Optimize discount strategy for profit balance  
- Promote digital payment adoption  
- Align promotions with peak sales times  

By applying these insights, the business can enhance **profitability, operational efficiency, and customer lifetime value**.

---

## 🧾 9️⃣ Project Learnings
- Applied **end-to-end data analysis workflow** from cleaning to insights.  
- Strengthened understanding of **EDA, business metrics, and storytelling with data**.  
- Improved ability to connect **technical analysis to business decisions**.

---

## 📁 1️⃣0️⃣ Repository Structure
📦 EDA-on-Sales-Dataset
│
├── 📂 data/
│ └── sales_dataset.csv
│
├── 📂 images/
│ ├── sales_by_country.png
│ ├── sales_by_category.png
│ ├── return_rate_by_country.png
│ ├── sales_over_time.png
│ ├── discount_vs_price_levels.png
│ ├── discount_vs_sales_(r=-0.22).png
│ └── sales_distribution_by_discount_levels.png
│
├── 📂 notebooks/
│ └── Sales_Data_Analysis.ipynb
│
├── 📄 README.md
└── 📄 LICENSE

---


---

### 🧩 Author
**Tushar Panwar**  
Data Science & Analytics Enthusiast  
📍 New Delhi, India  
📧 panwar259tushar@gmail.com  
💼 *Skilled in Python, SQL, Advanced Excel, Power BI, Tableau, and Machine Learning*

---

### ✅ Final Note
This project demonstrates the transition from **raw data to data-driven insights**, showcasing both **technical analysis** and **business interpretation** — an essential skillset for roles like **Data Analyst, Business Analyst, or MIS Executive**.
