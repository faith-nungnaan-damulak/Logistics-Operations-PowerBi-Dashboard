# Logistics Operations Analytics Dashboard

## 📊 Project Overview

This project is a Power BI logistics operations analytics dashboard developed as a capstone project.

The dashboard analyzes logistics operations from 2022–2024 across revenue, customers, delivery performance, detention, fleet utilization, fuel spending, maintenance, driver performance, and safety incidents.

The goal of the project was to transform multiple operational datasets into an interactive dashboard that helps identify performance trends, operational inefficiencies, and areas requiring management attention.

---

## 🎯 Business Questions

The dashboard was designed to answer questions such as:

- How is revenue performing over time?
- Which customers, lanes, and booking types generate the most revenue?
- What percentage of deliveries and pickups are completed on time?
- Where are the major delivery delays occurring?
- How much detention is occurring across the network?
- How is fuel spending changing over time?
- Which states have the highest fuel expenditure?
- What are the major maintenance cost categories?
- How effectively are trucks being utilized?
- What types of safety incidents occur most frequently?
- How many incidents are preventable?
- How does driver experience relate to on-time performance?
- Which terminals have the highest number of drivers?

---

## 🛠️ Tools & Technologies

- **Power BI** – Data modeling, DAX calculations, visualization, and dashboard development
- **Microsoft Excel / CSV** – Data inspection and preparation
- **DAX** – Measures, KPIs, and analytical calculations
- **Power Query** – Data transformation and preparation

---

## 📁 Dataset

The project uses multiple operational datasets covering:

- Customers
- Delivery events
- Drivers
- Driver monthly metrics
- Facilities
- Fuel purchases
- Loads
- Maintenance records
- Routes
- Safety incidents
- Trailers
- Trips
- Truck utilization metrics
- Trucks

The reporting period covered by the dashboard is **2022–2024**.

---

# 📈 Dashboard Pages

## 1. Revenue & Customers Overview

This page provides an overview of revenue generation and customer performance.

### Key metrics

- Total Revenue: **$262.53M**
- Total Loads: **85K**
- Average Revenue per Load: **$3.07K**
- Fuel Surcharge: **$29.98M**
- Active Customers: **168**

### Analysis includes

- Total revenue by month and year
- Revenue by booking type
- Top customers by revenue
- Top lanes by revenue
- Revenue by customer contract type
- Dry van vs refrigerated revenue

---

## 2. Delivery Performance & Detention

This page evaluates delivery and pickup performance across the logistics network.

### Key metrics

- On-Time Rate: **55.7%**
- Pickup On-Time Rate: **66.7%**
- Delivery On-Time Rate: **44.6%**
- Average Detention: **91.54 minutes**
- Detention Stop Rate: **86.8%**

### Analysis includes

- On-time performance by event type
- Monthly on-time trends
- On-time performance by facility
- On-time performance by weekday
- Detention time distribution
- On-time performance by booking type

### Key finding

Delivery performance is significantly lower than pickup performance, indicating that delivery operations are a major area for improvement.

---

## 3. Fleet, Fuel & Maintenance

This page analyzes fleet operating costs, fuel efficiency, maintenance spending, and truck utilization.

### Key metrics

- Fuel Spend: **$95.6M**
- Average Fuel Price: **$3.90**
- Average MPG: **6.50**
- Maintenance Cost: **$5.7M**
- Fleet Utilization: **83%**

### Analysis includes

- Average fuel price by month
- Fuel spend by year
- Fuel spend by state
- Maintenance cost by type
- Average utilization by month
- Fleet status

### Key finding

Fuel represents a significant operating expense, while variations in fuel efficiency and truck utilization provide opportunities for operational cost optimization.

---

## 4. Driver Performance & Safety

This page evaluates driver performance, safety incidents, claims, preventability, and driver experience.

### Key metrics

- Safety Incidents: **170**
- Total Claims: **$2.7M**
- Preventable Incidents: **37.6%**
- Injuries: **33**
- Active Drivers: **124**

### Analysis includes

- Incidents by type and fault
- Total claims by incident type
- Incidents by year
- Driver on-time rate distribution
- On-time performance by driver experience
- Drivers by home terminal

### Key finding

A significant proportion of incidents are preventable, highlighting opportunities for improved driver training, safety monitoring, and operational controls.

---

# 🔍 Key Insights

The analysis identified several important operational trends:

### Revenue

Revenue remained relatively stable across the reporting period, with no single month consistently dominating overall performance.

### Delivery Performance

Pickup performance (**66.7%**) is substantially stronger than delivery performance (**44.6%**), indicating that delivery execution is a major contributor to late events.

### Detention

Detention is widespread across the network, suggesting that delays are not isolated to a single facility and may require broader process improvements.

### Fuel & Fleet

Fuel represents one of the largest operating expenses, making fuel efficiency, vehicle utilization, and route optimization important areas for cost control.

### Safety

A considerable share of safety incidents are preventable, creating an opportunity to reduce operational risk through training, monitoring, and preventive safety measures.

---

# 📊 Data Model

The Power BI model combines multiple operational tables with a calendar table to support time-based analysis.

The calendar table covers:

**January 1, 2022 – December 31, 2024**

The model uses relationships between the calendar and operational tables to enable monthly, quarterly, and yearly analysis.

---

# 🧮 DAX & Calculations

Examples of analytical calculations used in the dashboard include:

- Total Revenue
- Total Loads
- Average Revenue per Load
- Fuel Surcharge
- Active Customers
- On-Time Percentage
- Pickup On-Time Percentage
- Delivery On-Time Percentage
- Average Detention Minutes
- Detention Stop Percentage
- Fuel Spend
- Average Fuel Price
- Average MPG
- Maintenance Cost
- Fleet Utilization
- Total Claims
- Preventable Incident Percentage
- Injury Count
- Active Driver Count

---

# 🎨 Dashboard Design

The dashboard uses a consistent visual design across all four pages.

### Design elements

- Navy section headers
- Teal, orange, green, and magenta accent colors
- KPI cards for high-level metrics
- Bar charts for ranking and comparison
- Line charts for trends
- Donut charts for categorical distributions
- Analytical insight boxes for key findings

The design was created to make operational trends easy to identify and interpret.

---

# 💡 Business Recommendations

Based on the analysis, management could consider:

1. **Improve delivery execution**
   - Investigate the causes of late deliveries.
   - Review delivery scheduling and route planning.
   - Monitor delivery performance by facility and weekday.

2. **Reduce detention**
   - Investigate facilities with recurring detention.
   - Improve appointment scheduling and loading/unloading processes.
   - Track detention trends regularly.

3. **Optimize fuel costs**
   - Monitor fuel efficiency by vehicle and driver.
   - Identify vehicles with consistently low MPG.
   - Review routing and vehicle utilization.

4. **Strengthen preventive maintenance**
   - Prioritize maintenance categories with the highest costs.
   - Use utilization and maintenance history to support preventive scheduling.

5. **Improve safety performance**
   - Analyze preventable incidents by type.
   - Strengthen driver safety training.
   - Monitor recurring incident patterns.

---

# 📷 Dashboard Preview

### Revenue & Customers

![Revenue & Customers Dashboard](Dashboard/page-1-revenue-customers.png)

### Delivery Performance & Detention

![Delivery Performance Dashboard](Dashboard/page-2-delivery-performance.png)

### Fleet, Fuel & Maintenance

![Fleet, Fuel & Maintenance Dashboard](Dashboard/page-3-fleet-fuel-maintenance.png)

### Driver Performance & Safety

![Driver Performance & Safety Dashboard](Dashboard/page-4-driver-performance-safety.png)

---

# 🚀 Skills Demonstrated

This project demonstrates practical experience in:

- Data analysis
- Data visualization
- Power BI dashboard development
- DAX
- Data modeling
- KPI development
- Time-series analysis
- Operational performance analysis
- Business intelligence
- Insight generation
- Data storytelling

---

# 👩🏽‍💻 Author

**Faith Nungnaan Damulak**

Aspiring Data Analyst | Power BI | Excel | SQL | Data Visualization

---

## 📌 Project Status

**Completed – 2026**
