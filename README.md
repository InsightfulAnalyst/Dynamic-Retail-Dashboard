# Dynamic-Retail-Dashboard
Welcome to the Walmart Retail Dashboard, a fully interactive Excel-based business intelligence solution designed to visualize and analyze Walmart's retail performance across various dimensions. This dashboard brings data to life using dynamic visuals, empowering users to make data-driven decisions with ease. 
An interactive Excel dashboard to analyze Walmart's retail performance. This dashboard provides insights into key business KPIs such as Profit, Sales, Profit Margin, Quantity, and Orders using dynamic visuals and slicers.
## 📊 Dashboard Features
- 📅 **Yearly Trends** of KPIs: Sales, Profit, Quantity, Orders, and Profit Margin
- 🎚️ **Slicers** for dynamic filtering and better user interaction
- 🥧 **Pie Charts** for category-wise KPIs
- 🍩 **Donut Charts** for KPIs summary
- 🗺️ **Map Chart** for Total Profit by Country
- 🪜 **Top & Bottom 5 Sub-Categories** based on each KPI
- 📈 **Scatter Plot** of Sales vs Profit

## **📊 Sample Data Tables**
### 🧾 **Order Table (Sample)**
| **Order ID**       | **Order Date** | **Segment**  | **Category**  | **Sub-Category** | **Sales** | **Quantity** | **Profit** |
|--------------------|----------------|--------------|---------------|------------------|-----------|--------------|------------|
| CA-2017-152156     | 2017-11-08     | Consumer     | Furniture     | Bookcases        | 261.96    | 2            | 41.91      |
| CA-2017-152156     | 2017-11-08     | Home Office  | Office Supplies    | Chairs           | 731.94    | 3            | 219.58     |
| US-2016-108966     | 2016-10-11     | Corporate    | Technology    | Phones           | 907.15    | 5            | 145.79     |

### 📦 **Return Table (Sample)**
| **Order ID**       | **Returned** |
|--------------------|--------------|
| CA-2017-152156     | Yes          |
| US-2016-108966     | No           |
| CA-2015-115812     | Yes          |

### 👥 **People Table (Sample)**
| **Region**  | **Person**         |
|-------------|---------------------|
| South       | Chris Turner        |
| West        | Michael Chen        |
| Central     | Cassandra Lopez     |

### 📈 **KPI Table with Symbols (Sample)**
| **KPI Name**       | **Display Name** | **Formula**           |
|--------------------|------------------|------------------------
| Total sales        | 📈               | SUM(Sales)            |
| Total Profit       | 💰               | SUM(Profit)           |
| Total qty          | 📦               | SUM(Quantity)         |
| No. of orders      | 🛒               | Count (Order ID)      |
| Profit margin      | 🔍               | SUM(Profit/Sum(Sales) |          

## **🧠 Problem Statements Solved**
The Dynamic retail dashboard answers several buisness questions, providing in-depth insights into key performance areas:

How are Walmart's key performance indicators (KPIs) trending over time?
→ Solved using yearly trend line charts for Sales, Profit, Quantity, and Orders.

![image](https://github.com/user-attachments/assets/5f3ed139-0c89-47b8-99ab-5245e4437210)





Which product categories and subcategories contribute the most or least to performance?
→ Solved using  bar charts for Top & Bottom 5 subcategories.

![image](https://github.com/user-attachments/assets/a621f1c2-1fbf-41fa-b496-7ee35e5a890e)








What is the geographical performance distribution (e.g., by country)?
→ Solved using a Map Chart displaying Total Profit by Country.

![image](https://github.com/user-attachments/assets/67580aa0-250e-4f01-9991-9625d418637d)







How can we visualize correlation between sales and profit to detect anomalies?
→ Solved using a Sales vs Profit Scatter Plot.

![image](https://github.com/user-attachments/assets/092ae1f1-26e7-4b2b-bc5f-f7eefea5e1dd)





Category-wise Profit 
→ Solved using  Pie chart

![image](https://github.com/user-attachments/assets/f42f88e6-a282-4532-9a0e-eafd0096ba25)







Segment-wise Sales share %
→ Solved using  Donut chart

![image](https://github.com/user-attachments/assets/39f05b42-1527-4015-8e28-e76825eb86bf)








How do different customer segments and regions affect business outcomes?
→ Solved using slicers and filters for dynamic analysis.

![image](https://github.com/user-attachments/assets/34c986ef-7d23-4387-bd51-343e9200345f)




---

## Snapshot of the Dashboard

![image](https://github.com/user-attachments/assets/c0f54aa1-99f9-4c01-922e-e173008edfed)






## 📌 Conclusion
This Walmart Retail Dashboard demonstrates how powerful insights can be extracted from structured data using nothing more than Microsoft Excel. By leveraging interactive features like slicers, charts, and maps, we transformed a flat dataset into a dynamic visual story that:

1. Identifies top and bottom-performing products

2. Reveals regional performance gaps

3. Highlights yearly growth patterns in key metrics

4. Provides actionable insights into sales and profitability

This project reflects not just data visualization but also business understanding, making it a great example of how Excel can be used as a business intelligence tool for decision-making.

