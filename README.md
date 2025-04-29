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

**📊 Sample Data Tables**
### 🧾 **Order Table (Sample)**
| **Order ID**       | **Order Date** | **Segment**  | **Category**  | **Sub-Category** | **Sales** | **Quantity** | **Profit** |
|--------------------|----------------|--------------|---------------|------------------|-----------|--------------|------------|
| CA-2017-152156     | 2017-11-08     | Consumer     | Furniture     | Bookcases        | 261.96    | 2            | 41.91      |
| CA-2017-152156     | 2017-11-08     | Consumer     | Furniture     | Chairs           | 731.94    | 3            | 219.58     |
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
