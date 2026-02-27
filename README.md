#  Airbnb Power BI Dashboard – Airbnb Trends New York City
An interactive Power BI dashboard analyzing Airbnb listings in New York City to uncover pricing patterns, neighborhood performance, and listing optimization opportunities.

---

## 📌 Overview

This project analyzes Airbnb listing data from New York City using Power BI to uncover insights related to pricing, availability, room types, and borough-level performance.

The goal is to identify market trends, evaluate neighborhood competitiveness, and highlight potential optimization opportunities for hosts and stakeholders.

The dashboard provides dynamic filtering and interactive visualizations for deeper data exploration.

---
## 🗂️ Project Structure

```
Airbnb-PowerBI-Dashboard-NYC/
│
├── Data/
│   └── airbnb_nyc_listings.csv
│
├── Dashboard/
│   └── Airbnb_NYC_Dashboard.pbix
│
├── Reports/
│   └── Airbnb_Insights_Report.docx
│
├── Images/
│   └── Dashboard_Screenshot.png
│
└── README.md
```
---

## 🎯 Problem Statement

The New York City Airbnb market is highly competitive, with thousands of listings across multiple boroughs and room types.

Key business questions addressed in this project:

- Which boroughs have the highest average prices?
- What room types generate the most revenue?
- Which neighborhoods dominate in listing count?
- How do availability and review activity affect performance?
- Are there optimization opportunities for underperforming listings?

This project answers these questions through interactive data visualization and analysis.

---

## 📊 Dataset Description

The dataset contains detailed information about Airbnb listings in New York City.

### Key Columns Include:

- id  
- name  
- host_id  
- neighbourhood_group (Borough)  
- neighbourhood  
- room_type  
- price  
- minimum_nights  
- number_of_reviews  
- reviews_per_month  
- availability_365  

Each row represents a unique Airbnb listing.

The dataset enables analysis of pricing trends, neighborhood performance, and listing behavior.

---
## 🛠️ Tools and Technologies

- Power BI  
- DAX (Data Analysis Expressions)  
- Data Cleaning & Transformation  
- Data Modeling  
- Interactive Visualization  

---

## 🔎 Methods

### 1️⃣ Data Preparation
- Cleaned missing and inconsistent values
- Structured dataset for analysis
- Created calculated columns and measures using DAX

### 2️⃣ Data Modeling
- Built relationships (if applicable)
- Created KPIs for core performance metrics

### 3️⃣ Dashboard Development
- Designed interactive visual elements
- Implemented dynamic filters for:
  - Room Type
  - Borough
  - Group categories
- Developed comparative visualizations for pricing and listing performance

---

## 📊 Dashboard Features

- Dynamic filters for room type, group, and borough
- KPI cards:
  - Total Listings
  - Average Price
  - Reviews per Month
- Top 10 neighborhoods by listing count
- Price vs. Minimum Nights scatter plot
- Average price by borough and room type
- Availability and review performance comparison

---

## 🔍 Key Insights

### 🏙 Manhattan Dominates Pricing
Manhattan listings have the highest average prices compared to other boroughs.

### 🏠 Entire Home/Apartment Leads the Market
Entire home/apartment is the most common and most expensive room type.

### 📈 Optimization Opportunities
Listings with high availability but low reviews suggest potential improvement areas in:
- Marketing
- Pricing strategy
- Listing presentation

### 🗺 Neighborhood Performance
A few neighborhoods contribute heavily to total listing counts, indicating concentrated competition zones.

---

## ▶️ How to Run This Project

1. Download the repository.
2. Open the file:
```
Airbnb_NYC_Dashboard.pbix
```
3. Open using Microsoft Power BI Desktop.
4. Interact with filters and visuals to explore insights.

Optional:
- Review `Airbnb_Insights_Report.docx` for summarized findings.
- View `Dashboard_Screenshot.png` for preview.

---
## 📈 Results and Conclusion

The Airbnb NYC market shows clear borough-level price differences, with Manhattan leading in premium pricing.

Entire homes dominate revenue potential, while shared and private rooms cater more to budget travelers.

Availability and review metrics highlight untapped potential for certain listings.

The dashboard enables data-driven decisions for hosts and market analysts to optimize pricing and performance strategies.

---

## 🚀 Future Work

- Add time-series trend analysis (monthly/yearly trends)
- Integrate occupancy rate analysis
- Build predictive pricing model
- Add geographic heatmap visualization
- Deploy dashboard to Power BI Service for live sharing

---

## 👩‍💻 Author

Ruchika Kumbhar  
Data Analyst | Aspiring Data Scientist  
Power BI | SQL | Python | Data Visualization  

---

## ⭐ Ending Note

This project is part of my data analyst learning journey. It demonstrates my ability to clean, analyze, and visualize real-world datasets using Power BI to generate actionable insights.

I’m continuously learning and open to feedback to improve my analytical and storytelling skills.

If you found this project helpful, feel free to star the repository!
