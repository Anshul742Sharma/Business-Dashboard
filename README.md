# Business-Dashboard
# Coffee Cup Business Performance Dashboard

An interactive executive dashboard built using **Power BI** to analyze and visualize the performance of *The Coffee Cup*, a national coffee chain in Canada. This project helps uncover key insights on sales, profit margins, budget variance, and product trends across multiple regions for the years 2023–2024.

## 📊 Project Objective

To develop a data-driven decision-support tool for senior management that:
- Identifies top-performing stores, cities, and products.
- Highlights budget vs actual performance variances.
- Analyzes profitability trends and marketing effectiveness.
- Enables slicing by market, product type, city, province, and more.

---

## 🧩 Dataset Description

The dataset represents transactional and planning data, containing fields such as:

| Column Name     | Description                                         |
|------------------|------------------------------------------------------|
| Date             | Date of transaction (2023–2024)                     |
| Store#           | Unique identifier for each store                    |
| Market / Province / City | Store location hierarchy               |
| Product / Product Type | Details of items sold                    |
| Sales / Profit / Margin | Financial metrics for performance analysis |
| Budget Sales / Profit / Margin | Planned (target) financial metrics |
| Marketing / Inventory / Total Expenses | Cost-related metrics        |

Additional calculated fields:
- Month-Year, Year, Quarter (for time-series visuals)
- Profit Margin, Sales Variance, Margin Variance, Total Operating Cost

---

## ⚙️ Data Cleaning & Transformation

- Converted text-formatted date fields to actual date type.
- Checked for and removed duplicates using a composite key (Store#, Date, Product).
- Standardized inconsistent casing and missing values.
- Verified location mappings (Market → Province → City).
- Created derived columns for temporal and variance analysis using DAX.

---

## 📌 Key Performance Questions (KPQs)

- Which provinces, markets, or cities generate the most revenue and profit?
- Are actual sales and profits meeting or exceeding budgeted values?
- Which product categories and individual items are the most profitable?
- What are the monthly and quarterly sales/profit trends?
- Which stores are underperforming against budget?
- How does marketing spend correlate with profitability?

---

## 📈 Dashboard Features

- Fully interactive dashboard with slicers for:
  - Year
  - Market size
  - Product Type
  - Region (Province/City)
- Visuals include:
  - Sales & Profit Trend Lines
  - Budget vs Actual Bar Charts
  - Top 5 Stores by Profit
  - Sales Distribution by Product Type
  - Marketing Spend vs Profit Bubble Chart

---

## 🧠 Recommendations

- Integrate forecasting models for improved planning.
- Add geolocation for spatial analysis.
- Track KPIs like customer loyalty and promotion effectiveness.
- Automate Power BI refresh for real-time insights.

---

## 🛠 Tools Used

- **Power BI**: Dashboard Development, Data Modeling, DAX
- **Excel / Power Query**: Data Preprocessing and Cleaning

---

## 👤 Author

**Anshul Sharma**  
Student ID: 100999334  
Course: Business Analysis and Assessments  
Submission Date: April 16, 2025

---

## 🏁 Outcome

The dashboard provides a solid foundation for performance tracking, real-time variance analysis, and data-driven decision-making for *The Coffee Cup*’s leadership. It offers strategic insights to optimize profitability across stores and improve budgeting accuracy.



