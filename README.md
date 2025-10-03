## About Dataset  
This dataset captures **key performance data** from a simulated marketing campaign, including spend, customer behavior, and business outcomes.  
- Each row represents a campaign on a specific date, with attributes such as impressions, clicks, leads, orders, and revenue.  
- **Source**: Kaggle  
- **Size**: 300 rows, 10 columns  
- **Main columns**: Date, Campaign Name, Category, Impressions, Clicks, Leads, Orders, Revenue, Marketing Spent  

The dataset enables analysis of important marketing KPIs, including:  
- **ROMI (Return on Marketing Investment)**  
- **CPC (Cost per Click)**  
- **CPL (Cost per Lead)**  
- **CAC (Customer Acquisition Cost)**  
- **AOV (Average Order Value)**  
- **CR (Conversion Rates)**  

---

## Business Questions  

1. **Marketing ROI & Efficiency**  
   - What is the overall ROMI?  
   - ROMI by campaigns → Which campaigns deliver the best return relative to spend?  

2. **Campaign Performance Over Time**  
   - Performance by date → When did we spend the most?  
   - When did we earn the most revenue?  
   - Analyze peak conversion rates and average order value.  

3. **Customer Behavior Analysis**  
   - When are buyers more active?  
   - Compare average revenue on weekdays vs weekends.  

4. **Campaign Type Effectiveness**  
   - Which campaign types work best (Social, Banner, Influencer, Search)?  

5. **Geo-targeting Strategy**  
   - Which geo-locations perform better: Tier 1 vs Tier 2 cities?  

---

## Methodology  

**Tools Used**  
- **DB Browser for SQLite**: Querying and manipulating the dataset using SQL.  
- **Google Sheets**: Visualizing results with bar charts, line charts, and comparison tables.  
- **Looker Studio**: Building an interactive dashboard for dynamic performance monitoring and insights discovery.  

**Workflow**  
1. Imported dataset directly into SQLite (no preprocessing needed).  
2. Wrote SQL queries to answer 5 key business questions about marketing performance.  
3. Exported query results into Google Sheets for visualization.  
4. Built **20+ visualizations** to analyze performance by campaign category, city tier, and day of week.  

**Key Metrics Calculated**  
- **ROMI** = Return on Marketing Investment → effectiveness of spend.  
- **CTR** = Click-through rate (Clicks / Impressions).  
- **CR1** = Visitor → Lead conversion rate (Leads / Clicks).  
- **CR2** = Lead → Order conversion rate (Orders / Leads).  
- **CPC** = Cost per Click (Marketing Spend / Clicks).  
- **CPL** = Cost per Lead (Marketing Spend / Leads).  
- **CAC** = Customer Acquisition Cost (Marketing Spend / Orders).  
- **AOV** = Average Order Value (Revenue / Orders).  
- **Gross Profit** = Revenue – Marketing Spend.  

These metrics were computed at multiple aggregation levels: **by campaign, by category, by city tier, and by weekday vs weekend** → enabling a comprehensive evaluation of marketing performance.  
