# SQL Sales Analysis
SQL-based sales analysis project using PostgreSQL to explore sales performance, profitability, customers, products, regions, and business KPIs.

## Project Objective
The objective of this project is to analyze sales data using SQL and answer practical business questions related to:
- Sales and revenue performance
- Customer purchasing behavior
- Product profitability
- Regional and state-level performance
- Category and segment performance
- Business KPIs

The analysis focuses on turning raw sales data into meaningful business insights using SQL.

## Dataset
The project uses a sales dataset containing information about orders, customers, products, locations, sales, discounts, and profits.
### Key fields include:
- Order ID
- Order Date
- Ship Date
- Customer ID
- Customer Name
- Segment
- Country
- City
- State
- Region
- Product ID
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

The dataset contains **400 orders and 166 customers**.

## Tools Used
- **PostgreSQL** — Database creation, data import, and sql analysis
- **SQL** — Data querying, aggregation, filtering, and business analysis

## SQL Techniques Demonstrated
This project demonstrates:
- Database and table creation
- Data import
- Data filtering using `WHERE`
- Conditional filtering using `AND` and `OR`
- Pattern matching using `LIKE`
- Range filtering using `BETWEEN`
- Sorting using `ORDER BY`
- Aggregations using `COUNT`, `SUM`, `AVG`, `MIN`, and `MAX`
- `GROUP BY` and `HAVING`
- Window functions
- `ROW_NUMBER()` and `RANK()`
- Common Table Expressions (CTEs)
- Subqueries
- Basic joins
- Business KPI analysis

## Analysis Performed
The SQL analysis covers:
- Regional sales performance
- Top customers by revenue
- Loss-making products
- State-level profitability
- Top products by profit
- Top-selling products within each category
- Customers performing above average sales
- State sales rankings
- Segment profitability
- Executive-level business KPIs

The complete SQL queries and analysis are available in:

`SQL_Portfolio_project.sql`

## Key Business Insights

### 1. Executive KPI Performance
The analysis covered **400 orders from 166 customers**, generating approximately:
- **Total Sales:** $105,224.98
- **Total Profit:** $3,665.46
- **Average Order Value:** $263.06

-These KPIs provide an overview of the sales volume, customer base, revenue, and profitability.

### 2. Most Profitable Segment
**Home Office** was the most profitable segment, generating approximately **$5,103.74** in total profit.

-Corporate and Consumer segments recorded negative total profit in the analyzed dataset.

### 3. State Sales Ranking
The top-performing states by total sales were:
1. **Texas** — $23,559.21
2. **California** — $15,950.31
3. **New York** — $14,564.24
4. **Pennsylvania** — $6,264.84

-Texas generated the highest total sales among the analyzed states.

### 4. Top-Selling Product by Category
The highest-selling products identified in each category were:
- **Furniture:** Riverside Palais Royal Lawyers Bookcase, Royale Cherry Finish
- **Office Supplies:** GBC DocuBind P400 Electric Binding System
- **Technology:** Lexmark MX611dhe Monochrome Laser Printer

### 5. Top 5 Products by Total Profit
The five highest-profit products were:
1. **Canon imageCLASS MF7460 Monochrome Digital Laser Multifunction Copier** — $1,995.99
2. **GBC DocuBind P400 Electric Binding System** — $1,415.43
3. **Hon Deluxe Fabric Upholstered Stacking Chairs, Rounded Back** — $805.13
4. **Canon PC1080F Personal Copier** — $701.99
5. **Logitech P710e Mobile Speakerphone** — $628.28

Conclusion
This project demonstrates how PostgreSQL and SQL can be used to perform sales analysis and translate raw business data into actionable insights.
The project progresses from fundamental SQL operations to advanced techniques while maintaining a practical business-analysis focus.
