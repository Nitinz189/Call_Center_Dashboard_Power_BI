
# 📞 Call Centre Data Analysis Dashboard

This is an end-to-end data analysis and visualization project that explores the performance of a fictional call centre. Designed using **Excel** for data wrangling and **Power BI** for dashboard creation, the project offers insights into service quality, employee efficiency, and revenue trends. It emphasizes SLA performance, strategic KPIs, and interactive data storytelling.

---

## 🧠 Objective

- Evaluate **SLA (Service Level Agreement) Compliance** using real-world metrics.
- Clean, structure, and relate raw datasets to enable multi-dimensional analysis.
- Create a comprehensive, visually driven dashboard that supports decision-making at every level—from agents to leadership.

---

## 🧹 Data Preparation: Excel Highlights

- **Formatted messy date fields** using advanced formatting and formula tricks.
- **Split multi-valued columns** to normalize the dataset structure.
- **Unpivoted** wide-format columns for simpler measure aggregation.
- Created a **Primary–Foreign key relationship** to enable table joins.
- Merged datasets to generate a unified analytical model.

### SLA Compliance Column
In the **Calls** table, I introduced a new column called `"SLA Compliance"` based on logic:
- If **Wait Time < 35 seconds**, then **“Within SLA”**
- Else, **“Outside SLA”**

This allowed quick assessment of customer service timeliness.

---

## 📊 Dashboard Walkthrough

### 🔹 1. **Executive Overview**
![Dashboard Overview](images\Overview.png)

- Displays **total calls, average wait time, SLA rate, revenue**, and other key indicators.
- Summarizes call distribution by **type, site**, and **SLA compliance**.
- Highlights business efficiency with metrics like *Revenue per Call* and *Calls per Employee*.

---

### 🔹 2. **Employee Performance Analysis**
![Dashboard Overview](images\Employee.png)

- Analyzes individual employee metrics: **call volume, SLA%, average wait time**.
- Scatter plots surface outliers—employees excelling or needing support.
- Table ranks employees across multiple service KPIs.

---

### 🔹 3. **SLA Compliance Deep Dive**
![Dashboard Overview](images\SLA.png)

- Compares SLA adherence across **sites, call types**, and **managers**.
- Interactive breakdowns enable quick identification of service gaps.
- Manager SLA performance helps evaluate leadership effectiveness.

---

### 🔹 4. **Revenue Performance**
![Dashboard Overview](images\Revenue.png)

- Shows **total and per-call revenue** across locations and service lines.
- Visualizes sales trends over time to uncover seasonality.
- Ranks managers by revenue contribution, identifying top performers.

---

### 🔹 5. **Global Filter Page**
![Dashboard Overview](images\Filter.png)

- A centralized filtering tool that **syncs across all report pages**.
- Users can slice by **date, manager, employee, site**, and **call type**.
- Enhances usability and helps maintain consistent context across views.

---

## 🧭 Key Learnings

- Strengthened my foundation in **data modeling, dashboard design**, and **ETL concepts**.
- Applied logical thinking to clean, structure, and connect disparate datasets.
- Developed interactive visuals that communicate insights clearly to non-technical stakeholders.
- Learned to interpret business KPIs through the lens of both **operations** and **customer experience**.

