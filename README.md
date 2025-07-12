## Project Title / Headline :
Blinkit Sales Analytics: Interactive Dashboard Built with Power BI, PostgreSQL & Python.

## Short Description / Purpose :
Built an end-to-end sales analysis dashboard for Blinkit using Power BI, PostgreSQL, Excel, and Python, showcasing KPIs like total sales, average rating, item categories, and outlet performance. Enabled dynamic filtering by outlet size, location, and item type to uncover business insights and support strategic decisions.

## Technologies Used :

1. **Python** – Used to **import and insert Blinkit sales data into PostgreSQL**, leveraging libraries such as:

   * `pandas` – For reading and structuring data from Excel/CSV files.
   * `sqlalchemy` / `psycopg2` – For establishing connections and executing insert operations to PostgreSQL.

2. **PostgreSQL** – Served as the **primary database** for storing cleaned sales data. SQL queries were used for aggregations, filtering, and data preparation for Power BI.

3. **Microsoft Excel** – Used as a **source file** containing raw sales data and sometimes for early-stage formatting.

4. **Power BI** – The main tool for building the **interactive sales dashboard**, including:

   * Visualizations (bar charts, line graphs, KPI cards, maps, etc.)
   * Slicers for outlet size, fat content, item type, and city
   * Page-level and report-level filters for deeper insights

5. **DAX (Data Analysis Expressions)** – Used to create calculated **measures and KPIs** (e.g., total sales, sales %, average rating) within the Power BI data model.

6. **Power Query (M Language)** – Used to **clean and transform** data from PostgreSQL before loading it into the Power BI model (e.g., data type changes, column filtering, null handling).

## Features / Highlights :

#### • **Business Problem:**

Blinkit, an online grocery delivery service, needed a clear, centralized view of its sales performance across product types, outlet sizes, and regions to identify trends, optimize operations, and improve decision-making.

#### • **Goal of the Dashboard:**

To design an interactive Power BI dashboard that enables stakeholders to monitor key sales metrics, evaluate outlet and product performance, and extract actionable insights from large volumes of sales data stored in PostgreSQL.

#### • **Walkthrough of Key Visuals:**

* **KPI Cards:** Showcased total sales, average rating, average sales and item counts at a glance.
* **Bar Charts:** Compared sales by outlet size, item fat content, and item type.
* **Donut/Column Charts:** Visualized sales distribution across outlet types and item categories.
* **Map Visual:** Displayed city-wise or region-wise sales distribution.
* **Slicers & Filters:** Enabled dynamic filtering by outlet size, item type, fat content, and city for custom analysis.

#### • **Business Impact & Insights:**

* Enabled real-time visibility into top-selling product categories and underperforming outlets.
* Helped identify high-performing outlet sizes and optimal product mix for targeted marketing.
* Improved cross-functional reporting by consolidating sales KPIs into a single interactive dashboard.
* Supported data-driven decision-making by making sales trends, customer preferences, and regional performance easily accessible to business teams.






                      
