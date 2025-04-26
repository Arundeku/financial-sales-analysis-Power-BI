# Global Sales Dashboard Project

An end-to-end analytics solution built in Power BI, visualizing global sales data to drive strategic business decisions. By transforming the Global Superstore 2016 dataset into an interactive dashboard, stakeholders can uncover revenue drivers, profitability insights, and seasonal patterns across multiple regions and product lines.

---

## 🚀 Project Objectives

1. **Holistic Sales Overview:**  
   - Present total revenue, profit, and unit sales at a glance.  
2. **Regional & Country Analysis:**  
   - Compare performance across 13 regions and key countries (e.g., USA, Australia, France).  
3. **Category & Segment Insights:**  
   - Drill down into Technology, Furniture, and Office Supplies.  
   - Evaluate customer segments (Consumer, Corporate, Home Office).  
4. **Time‐Series & Seasonality:**  
   - Track monthly trends (2012–2015), identify peaks (Nov 2015) and troughs (Feb 2013).  
5. **Data‐Driven Action:**  
   - Highlight underperforming markets and product lines for targeted improvement.  
   - Inform promotional calendar and inventory strategies via seasonality insights.

---

## 📊 Dataset Details

- **Source File:** `global_superstore_2016.xlsx`  
- **Records:** 49,994 orders spanning Jan 2012–Dec 2015  
- **Key Columns & Descriptions:**  

  | Column Name    | Description                                         |
  | -------------- | --------------------------------------------------- |
  | **Order ID**       | Unique order identifier                           |
  | **Order Date**     | Date the order was placed                          |
  | **Ship Date**      | Date the order was shipped                         |
  | **Customer ID**    | Unique customer identifier                         |
  | **Customer Name**  | Full name of the customer                          |
  | **Segment**        | Customer segment (Consumer / Corporate / Home Office) |
  | **Country**        | Destination country of the order                   |
  | **Region**         | Continent‐level region (e.g., Western Europe)      |
  | **Product ID**     | Unique product identifier                          |
  | **Category**       | High‐level product category (Technology, Furniture, Office Supplies) |
  | **Sub‐Category**   | Granular product division                          |
  | **Product Name**   | Descriptive name of the product                    |
  | **Sales**          | Revenue generated (USD)                            |
  | **Quantity**       | Number of units sold                               |
  | **Discount**       | Discount applied (%)                               |
  | **Profit**         | Profit earned (USD)                                |

---

## 🎨 Power BI Dashboard

- **Interactive Filters:**  
  - Slicers for Region, Category, Segment, Date Range  
- **Visual Pages:**  
  1. **Overview** – High-level KPIs: Total Sales, Total Profit, Average Discount  
  2. **Regional Analysis** – Maps & bar charts comparing regions & countries  
  3. **Category Performance** – Treemaps and stacked bars for category/sub-category  
  4. **Segment Profitability** – Profit by customer segment  
  5. **Seasonality** – Line charts showing monthly sales trends  
- **Key Takeaways:**  
  - Western Europe leads sales; USA leads among countries.  
  - Technology is the top revenue driver.  
  - Consumer segment yields highest margin.  
  - Significant seasonality with end-year peaks; early-year dips.

---

## 🔧 Tools & Technologies

- **Data Preparation:** Microsoft Excel  
- **Analytics & Scripting:** Python (pandas, matplotlib)  
- **Visualization & Reporting:** Power BI Desktop  
- **Presentation:** Microsoft PowerPoint  

---

## 📂 Repository Structure
global-sales-dashboard/
│
├── global_superstore_2016.xlsx                 # Raw dataset used for analysis
├── Global Sales Dashboard Project.pbix         # Power BI dashboard file
├── global_sales_dashboard_summary_updated.pptx # PowerPoint presentation of insights
├── README.md                                   # Project overview and documentation
└── assets/                                     # (Optional) Folder for screenshots or visuals
