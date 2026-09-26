# JCars-Logistics-Performance
This documentation is about JCars Logistics Power BI solution, prepared from Jcars_Data.pbix. The file contains an Executive Dashboard (Page 1), Branches Performance (Page 2), Sales and revenue Trends (Page 3), Vehicle and Inventory (Page 4), Customer and SalesRep (Page 5) built on a star schema of FactSales, Dim_Customer, Dim_SalesRep, Dim_Vehicle, Dim_Location and Dim_Date, with measures already defined for Total Sales Revenue, Gross Profit, Total Cars Sold, Total Transactions, Returned Transactions, Average Revenue per Car/Order and Average Customer Rating. This documentation specifies the layout for each, the assumptions/insights and recommendations sections.
# How the Pages Work Together
The Executive Dashboard is the entry point: five KPI cards plus revenue trend, branch comparison and sales-rep visuals give management a one-glance read of the business. Every subsequent page answers a narrower question the dashboard raises.
Every detail page carries a slicer panel, so filters set on one page can sync where the analysis calls for it.

<img width="495" height="242" alt="Dash" src="https://github.com/user-attachments/assets/0bf18292-ef8f-4a35-bd42-47e150b4bd6f" />

<img width="155" height="262" alt="Slicer" src="https://github.com/user-attachments/assets/7fce11ed-030a-4e04-b5c3-ff653eac48a4" />

# Detailed Report Pages
### 1. Executive Dashboard
   
Purpose:	One-glance monitoring: Key KPIs and trends, branch, SalesRep, Region, Car models performance.

Key KPIs:	Total Revenue, Total Cars Sold, Gross Profit, Avg Revenue per Order, Avg Revenue per Car.

Main visuals:	Line chart (revenue over time), Bar Chart (Total cars sold by model), Column chart (SalesRep performance), Donut chart (Transaction by payment status), Map (Regional/County/city performance)

<img width="495" height="242" alt="Final Dashboard" src="https://github.com/user-attachments/assets/a5b408ec-a015-4d15-9bc6-683fa626050e" />

### 2. Branches & Geographic Performance 

Purpose:	Identify where performance is strongest/weakest by branch and region, for investigation.

Key KPIs:	Revenue and Cars Sold by branch; Profit Margin %; Avg Rating by branch.


Main visuals:	Map (Revenue/Cars sold by branch location), Bar chart (revenue by branch), Matrix (Branch KPI by Revenue, Profit, Cars sold, and avg rating, top/bottom 5 (bar).

<img width="495" height="242" alt="Branch Performance" src="https://github.com/user-attachments/assets/9c843a72-af24-4c17-90ee-bfa90ac7de2e" />

### 3. Sales & Revenue Trends

Purpose:	Explain what happened to revenue over time and which segment or channel drove it.

Key KPIs:	MoM growth %, YoY growth %

Main visuals:	Dual-axis line chart (revenue & transactions, monthly, with trend line), Revenue by customer type and month (column chart),  revenue by channel over time (stacked area)

<img width="495" height="242" alt="Sales Trend" src="https://github.com/user-attachments/assets/2e9b2de4-8aa0-4012-a2a2-356351bec35f" />


### 4. Vehicles & Inventory Performance

Purpose:	Understand which models/categories sell, at what price point and margin.

Key KPIs:	Units sold by model, avg revenue per car, return rate by model

Main visuals:	Cars sold by model (bar chart), avg revenue per car by model/category (donut), sales volume vs avg rating (scatter), Car model (Slicer)

<img width="495" height="242" alt="Vehicle " src="https://github.com/user-attachments/assets/f674a90f-5727-46a0-84a4-e7710f105795" />


### 5. Customers, Sales Reps

Purpose:	Understand who is buying, who is selling, and through which channel.

Key KPIs: 	Revenue by customer type, Salesrep Performance vs customer rating 

Main visuals:	Revenue by customer type (donut), Salesrep Performance vs customer rating (Scatter)

<img width="495" height="242" alt="Customer sales" src="https://github.com/user-attachments/assets/578a775d-3f0d-422c-9f31-f8811956240f" />


# Dashboard & Report Design Standards

• Currency: all monetary values standardised and displayed in Kenya Shillings (KES)

•	Colour palette: navy/blue family for structure and emphasis

•	Consistency: identical fonts, KPI card style, title-bar treatment, and navigation bar on every page.

•	Visual hierarchy: KPI cards top-of-page, trend/comparison visuals middle, supporting detail tables bottom — the same reading order on every page.

# Assumptions

Currency: All final management monetary analysis should use KES.

Unspecified currency: Where a monetary value did not explicitly identify currency, it was treated as KES, following the assessment.

Missing values: Blank does not automatically mean zero.

Duplicate transaction IDs: Repeated IDs may represent separate transactions; Transaction Key added.

Negative review count: Treated as sign/scraping artifact in Review Count.





