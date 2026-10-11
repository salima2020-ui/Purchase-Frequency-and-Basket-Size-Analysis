# Purchase-Frequency-and-Basket-Size-Analysis

## Project Overview
This project performs a comprehensive **Exploratory Data Analysis (EDA)** and **Customer Segmentation** on a retail grocery sales dataset. The primary goal is to uncover hidden purchasing patterns, analyze product demand, track temporal sales trends, and segment customers based on their shopping frequency to derive actionable business insights.

## Dataset
* **Source:** Groceries dataset containing transactional records including member numbers, purchase dates, and purchased item descriptions.
* **Key Features:** 
  * `Member_number`: Unique identifier for each customer.
  * `Date`: The timestamp of the transaction.
  * `itemDescription`: The specific product bought in each transaction.

---

## Project Workflow & Analysis Steps
1. **Data Preprocessing & Cleaning:** Standardizing date formats and preparing transactional structures.
2. **Purchase Frequency Distribution:** Analyzing how often customers visit the store using unique date aggregation (`nunique`).
3. **Top Product Demand:** Identifying the top 10 most frequently purchased items using horizontal bar visualizations.
4. **Weekly Sales Distribution:** Examining transaction volumes across days of the week.
5. **Monthly Sales Trends:** Tracking long-term sales patterns over time using time-series line charts.
6. **Customer Segmentation:** Grouping customers into distinct tiers (Low, Medium, High Frequency) using custom logic and visualizing proportions with a dark-themed donut chart.

---

## Key Business Insights

### 1. Customer Loyalty & Visit Frequency
* **Observation:** The vast majority of customers fall into the **Low Frequency** category (visiting only 1–2 times). This indicates that the store relies heavily on one-time or casual shoppers rather than repeat traffic.
* **Recommendation:** Implement targeted marketing campaigns, loyalty programs, and personalized discounts to encourage casual shoppers to return more frequently.

### 2. Top Product Demand & Inventory Management
* **Observation:** The top 10 most purchased items are predominantly daily essential grocery products. 
* **Recommendation:** Ensure continuous stock availability and optimal inventory positioning for these high-demand items to prevent stockouts and safeguard baseline revenue.

### 3. Weekly Sales Patterns
* **Observation:** Transaction volumes fluctuate noticeably across different days of the week, highlighting peak shopping windows.
* **Recommendation:** Optimize staff scheduling, manage supply chain flow, and time promotional push notifications or flash sales to align with these high-traffic days.

### 4. Long-Term Monthly Sales Trends
* **Observation:** Time-series analysis of monthly sales reveals seasonal peaks and troughs over the recorded timeline.
* **Recommendation:** Utilize these historical trends for more accurate demand forecasting, seasonal budget planning, and evaluating the ROI of past marketing initiatives.

---

## Tech Stack & Libraries
* **Python**
* **Pandas** (Data manipulation & aggregation)
* **Matplotlib** (Customized data visualization with dark-mode aesthetic)
