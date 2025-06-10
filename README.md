# E-commerce Customer & Sales Analysis: Actionable Insights for Strategic Growth

##  Overview
This project explores customer behavior, product performance, and Revenue trends within an e-commerce platform. Using transactional data, we uncover **key revenue drivers**, detect **Best selling products**, and surface **data-backed insights** to guide business strategy.

---

## Problem Statement
E-commerce platforms deal with high volumes of sales, returns, and customer activity. However, decision-makers often lack **clear visibility into customer segments, sales trends, and product performance**.

This project answers:
- Which categories and products generate the most revenue?
- What are the peak performing sales months?
- What factors contribute to higher sales?
- what is the customer retention rate?

---

##  Dataset Summary
- **Records:** ~50,000+ transactions
- **Fields:**  
  - `Transaction_Id`, `Customer_Id`, `Product_Id`  
  - `Transaction_Date`, `Units_Sold`, `Discount_Applied`  
  - `Category`, `Revenue`

---

##  KPIs Analyzed
| KPI | Description |
|-----|-------------|
| **Total Revenue** | Overall business volume |
| **Monthly Revenue Trends** | Seasonality and dips |
| **Top Products & Categories** | Product performance |
| **Revenue by Product Category** | Valuable segments |
| **Customer Retention and Revenue** | High-value customer profiling |

---

## Analysis Breakdown

###  Top Categories by Revenue

-  **Goal**: Identify High revenue generating categories 
-  **Graph**: 
![Category wise revenue](""C:\Users\AMISHA GUPTA\Pictures\Screenshots\category wise revenue.png"")
-  **Insight**:  
  The top performing category is books with $5666623.17 in revenue.it is suggested to prioritize for upcoming campaigns and stock planning. to implement a recommendation system based on purchase history and Bundle books with related merchandise to enhance revenue growth.

---

###  Top selling products

-  **Goal**: Identify what products are the most purchased
-  **Graph**:![Top 10 products by units sold](""C:\Users\AMISHA GUPTA\Pictures\Screenshots\top 10 products by units sold.png")
-  **Insight**:  
  Products 215, 614, and 785 demonstrate strong sales performance, indicating potential demand for bulk purchasing. Leveraging targeted discounts or volume-based pricing strategies could further optimize revenue growth.
---

### Top 10 Customers by Revenue

- **Goal**: Rank customers by total revenue
-  **Graph**: ![Graph Title]("C:\Users\AMISHA GUPTA\Pictures\Screenshots\top 10 customers (revenue).png")
-  **Insight**:  
 The top 10 customers contribute **$74,488 in total revenue**, representing a highly valuable segment. Implementing targeted incentives, such as exclusive offers and early-access privileges, can enhance retention and strengthen long-term customer engagement.

---

###  Revenue share by Region

-  **Goal**: Estimate which regions generate highest revenue.
- **Graph**: ![Revenue share by region]("C:\Users\AMISHA GUPTA\Pictures\Screenshots\revenue share by region.png")
-  **Insight**:  
  The revenue distribution shows **Europe leading at 33.5%, with North America and Asia closely following at 33.3% each**, indicating a need for balanced strategic investments. Europe’s slight edge presents an opportunity for targeted market expansion to optimize growth.

---

###  Repeat Purchase Rate

-  **Goal**: Analyze Customer retention and new buyer ratio.
- **Graph**: ![Repeat Purchase Rate Breakdown]("C:\Users\AMISHA GUPTA\Pictures\Screenshots\repeat purchase rate breakdown.png")
-  **Insight**:  
  The **repeat purchase rate** shows that **77.6% of customers are repeat buyers, while 22.4% are one-time buyers**, highlighting strong customer retention. This suggests an opportunity to further nurture loyalty programs and targeted engagement strategies.
---
###  Monthly Revenue Distribution

- **Goal**: Analyze the total revenue records to identify the best performing month.

-**Graph**: ![Total revenue by momth]("C:\Users\AMISHA GUPTA\Pictures\Screenshots\total revenue by month (2).png")
- **Insight**:  
  The **monthly revenue analysis** highlights **peaks in March and November, with a noticeable drop in September**, indicating seasonal demand shifts. Adjusting marketing strategies and inventory planning during lower-performing months could help stabilize revenue.

  ### **Strategic Recommendations for Business Growth**  

Based on the data insights, here are **actionable strategies** to enhance revenue, customer retention, and operational efficiency:  

#### **1. Optimize Category Performance**  
- Prioritize **books** in inventory and marketing, given their **5,666,623 revenue dominance**.  
- Introduce **bundled offers** and personalized recommendations to maximize engagement.  

#### **2. Strengthen Customer Loyalty & Retention**  
- With **77.6% repeat purchase rate**, introduce **exclusive membership perks** to further increase retention.  
- Develop a **targeted engagement strategy** for the **22.4% one-time buyers** to encourage repeat purchases.  

#### **3. Enhance Pricing & Bulk Purchase Strategy**  
- Products **215, 614, and 785** demonstrate **high sales volume**, indicating demand for bulk orders.  
- Introduce **tiered discount structures** to capitalize on bulk purchasing behavior.  

#### **4. Optimize Seasonal Demand & Revenue Fluctuations**  
- Revenue **peaks in March and November**, but **dips in September**—launch **seasonal promotions** to address demand gaps.  
- Implement **dynamic inventory planning** aligned with **high-performing months** for better stock management.  

#### **5. Expand Market Presence Strategically**  
- **Europe leads revenue at 33.5%**, with **North America and Asia close behind (33.3%)**—invest in localized campaigns to enhance share in all regions.  
- Focus on **Europe’s slight advantage** with **targeted expansion strategies** to solidify market dominance.  

##  Summary of Insights

| Theme | Insight |
|-------|---------|
| | Category Revenue| Books lead with **5,666,623 revenue** while others show similar demand indicating linear demand|

|Repeat Purchase Rate | 77.6% repeat buyers, strong retention potential.|

|Top Customers| Top 10 customers generate 74,488 revenue, indicating a high-value segment for retention strategies.|

|Revenue Share by Region| Europe leads at 33.5%, with North America and Asia close at 33.3%, indicating balanced market distribution.|

| Monthly Revenue Trends| Revenue peaks in March and November, with a dip in September, indicating seasonal demand shifts.|

|Top-Selling ProductS| Products 215, 614, and 785 lead in unit sales, suggesting bulk orders or pricing optimization opportunities.|

---

##  Tools Used

- **Excel** ( Data cleaning)
- **Python** (EDA & scripting)
- **Pandas** (Data manipulation)
- **Matplotlib / Seaborn** (Visualizations)
- **Colab** (Development environment)
---
##  How to Test This Project

This project is structured to help recruiters and business stakeholders easily review real-world data analysis and insights.

 **View the notebook here**: [Open in Google Colab]
(https://colab.research.google.com/drive/1HPcAU5XofgZr_iH0aD1gWfScBqUC6BeA#scrollTo=R0cI-AqGu7kG)

### What to do:
- Run the notebook from top to bottom 
- Each section includes:
  - Business question or KPI
  - Code + clean graph
  - A brief **"Key Insight"** written below each chart



## Final Thoughts
This analysis provides data-driven insights into customer behavior, revenue patterns, and market opportunities. Implementing the recommended strategies can drive growth, enhance retention, and optimize business performance.
For future analysis, exploring customer lifetime value, demand forecasting, and predictive analytics could unlock long-term revenue potential. Continuously refining marketing and pricing strategies based on seasonal trends will further strengthen business adaptability.


