# African Logistics Performance Optimization

## Project Overview

Efficient logistics systems are essential for economic development and trade growth across African markets. However, logistics operations often face challenges including delivery delays, infrastructure limitations, and cost inefficiencies.

This project analyzes logistics performance across multiple African countries using data analytics and visualization techniques to identify operational bottlenecks and propose optimization strategies.

The analysis combines **R for data analysis** and **Tableau for interactive visualization**, enabling strategic insights for logistics performance improvement.

---

# Business Context

Supply chain efficiency is a critical competitive advantage for logistics operators across emerging markets.

African logistics networks face structural challenges including:

- long transportation distances
- infrastructure constraints
- variable delivery reliability
- high operational costs

Improving logistics efficiency can significantly enhance delivery performance, customer satisfaction, and operational profitability.

---

# Business Problem

How can data analytics identify inefficiencies in logistics operations and support data-driven decision making to improve supply chain performance across African markets?

---

# Dataset

The dataset contains **5000 simulated logistics shipments across African logistics networks**.

Each record represents a shipment transaction including operational and financial attributes.

### Key Variables

- Country
- City
- Warehouse
- Transport Mode
- Distance (km)
- Delivery Time (days)
- Expected Delivery Time
- Shipping Cost
- Order Value
- Order Date

Dataset location in repository: [data/logistics_dataset.csv](data/logistics_dataset.csv)

---

# Analytical Methodology

The analysis follows a structured data analytics workflow.

## 1 Data Preparation

Performed using **R**

Key steps:

- Data cleaning
- Delivery delay calculation
- Feature transformation
- Data formatting for visualization

Notebook location: [notebooks/African_Logistics_Analysis.Rmd](notebooks/African_Logistics_Analysis.Rmd)


---

## 2 Exploratory Data Analysis

The exploratory analysis focuses on identifying patterns in logistics operations such as:

- shipment distribution across countries
- delivery delay patterns
- shipping cost vs distance relationships
- shipment demand trends over time

These analyses help uncover operational inefficiencies and performance variability across logistics networks.

---

# Tableau Strategic Dashboard

A strategic dashboard was developed in Tableau to visualize logistics performance indicators.

Dashboard file location: [dashboard/logistics_dashboard.twbx](dashboard/logistics_dashboard.twbx)


The dashboard provides a visual overview of:

- logistics shipment distribution
- average delivery delays
- transport mode performance
- shipping cost efficiency
- demand trends

---

# Dashboard Preview

![African Logistics Dashboard](images/african_logistics_dashboard.png)

---

# Analysis Charts

The following charts were produced in R during the exploratory analysis. The full rendered report is available in [notebooks/African_Logistics_Analysis.html](notebooks/African_Logistics_Analysis.html).

### Total Shipments by Country

![Total Shipments by Country](images/shipments_by_country.png)

### Average Delivery Delay by Country

![Average Delivery Delay by Country](images/delivery_delay_by_country.png)

### Delivery Delay by Transport Mode

![Delivery Delay by Transport Mode](images/delivery_delay_by_transport_mode.png)

### Shipping Cost vs Distance

![Shipping Cost vs Distance](images/cost_efficiency.png)

### Shipment Volume Over Time

![Shipment Volume Over Time](images/shipment_trend.png)

---

# Key Insights

## Delivery Delay Patterns

Certain logistics corridors show significantly higher delivery delays, indicating potential infrastructure constraints or route inefficiencies.

## Transport Mode Performance

Road transportation shows the highest variability in delivery time, suggesting opportunities for route optimization and scheduling improvements.

## Cost Efficiency

Shipping costs generally increase with transport distance, but some routes display cost anomalies that may indicate operational inefficiencies.

## Shipment Demand Growth

Shipment volume trends indicate increasing logistics demand, reinforcing the importance of scalable logistics infrastructure and optimized operational planning.

---

# Strategic Recommendations

Based on the analysis, several operational improvements can be implemented.

### Route Optimization

Identify and optimize high-delay logistics corridors using route performance analytics.

### Transport Mode Optimization

Improve allocation of transport modes depending on shipment distance, urgency, and infrastructure availability.

### Predictive Monitoring

Deploy predictive analytics models to detect high-risk shipments likely to experience delays.

### Cost Efficiency Metrics

Develop operational KPIs to monitor logistics cost efficiency across routes and transport modes.

---

# Tools & Technologies

This project uses the following analytics stack:

- R
- R Markdown
- Tableau
- Data Visualization
- Supply Chain Analytics

---

# Repository Structure

african-logistics-performance-optimization

README.md

data/
logistics_dataset.csv

notebooks/
African_Logistics_Analysis.Rmd
African_Logistics_Analysis.html

dashboard/
logistics_dashboard.twbx

images/
african_logistics_dashboard.png
shipments_by_country.png
delivery_delay_by_country.png
delivery_delay_by_transport_mode.png
cost_efficiency.png
shipment_trend.png
social_preview.png

---

# Author

Franck Djandja

Data Analyst | Business Intelligence | Predictive Analytics

Focus Areas:
- Fintech Analytics
- Logistics & Supply Chain Analytics
- Industrial Data Analytics in Africa
