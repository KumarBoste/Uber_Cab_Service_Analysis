# 🚖 Uber Cab Service Analysis – Power BI Project Report
![Uber Logo](https://github.com/KumarBoste/Uber_Cab_Service_Analysis/blob/main/Icons/Uber%20Logo.png)

## Project Overview
The Uber Cab Service Analysis project aims to evaluate the overall performance, demand trends, customer behavior, and revenue patterns of a cab service company using Power BI.
The project integrates real-world ride-level data containing trip details, customer demographics, distance covered, ride outcomes, payment modes, and driver performance.

By designing interactive dashboards, the project helps stakeholders:
- Monitor booking trends across months, quarters, and vehicle types
- Evaluate customer and driver performance
- Track operational KPIs like completed bookings, cancellations, and lost bookings
- Understand revenue patterns and high-demand locations
- Make data-driven decisions to optimize fleet, pricing, and customer experience

## Problem Statement
With increasing demand for online cab services, companies must continuously improve their operations to stay competitive.

However, the business faces challenges such as:
- High cancellation and lost-booking counts
- Revenue variations between cities and vehicle types
- Identifying peak hours and underperforming zones
- Customer dissatisfaction and inconsistent driver ratings
- Inefficiencies across payment modes and distance optimization

This project provides insights to answer:
- Which vehicle types contribute the most to revenue?
- What are the peak hours and high-demand locations?
- What are the major reasons for ride cancellations?
- How do customer/driver ratings impact service quality?
- Which factors influence booking completion rates?

## Statistical Analysis
Key statistical insights derived from the dataset:
### 1. Summary Metrics

| Metric	| Value |
|---------|-------|
| Completed Bookings | 93K |
| Lost/Cancelled Bookings | 57K |
| Total Revenue | 52M |
| Total Distance | 2.51M km |
| Average Distance per Trip | 24.64 km |

### 2. Vehicle-Level Statistics
- Auto generated highest revenue (12.9M) and largest customer base
- Bike and Go Mini contributed significantly with low fuel cost & high demand
- Uber XL had lowest revenue & customer count

### 3. Time-Series Analysis
- Highest demand observed in January, March, June, and August
- Lowest performance in February (seasonality dip)

### 4. Customer Behaviour
- First-time riders: 48K
- Return riders: 5650
- Regular riders (3+ rides): 11K
- This indicates a growing but moderately loyal customer base.

### 5. Ratings
- Average Customer Rating: 4.40
- Average Driver Rating: 4.23
- Both ratings fall inside healthy performance range.

## Data Visualizations & Insights
Below are insights derived from each dashboard:

### 1. Overview Dashboard
Quick KPIs show healthy booking volume but high lost bookings (57K).
Bookings follow a cyclical pattern, rising in summer and dipping in Feb.
Revenue is strongly correlated to seasonality & travel months.

### 2. Vehicle Dashboard Insights
- Auto, Bike, and Go Mini are the top 3 revenue contributors.
- Customer satisfaction is higher in economical categories.
- Uber XL is underperforming → possible reasons:
- Higher price
- Limited demand
- Lower availability

### 3. Revenue Dashboard
- Revenue by Payment Mode
- UPI (23M) is the most used payment mode → indicates digital adoption.
- Lowest revenue from Debit Card (4M).
- Revenue by Location
-Top pickup locations:
  - Khandasa, Barakhamba, Saket, Badarpur
- These zones have high density and active commuting population.

### 4. Customer Dashboard
- Customer trends show steady monthly ride patterns.
- Top customers generate 5K–7K revenue annually.
- Cancels occurred mostly due to:
  - No driver availability
  - Customer demand change
  - Technical/other issues
  
### 5. Distance Dashboard
- Total distance (2.51M km) is heavily driven by Auto, Bike, and Go Mini.
- Heatmap of Time Slots shows:
    - Peak hours: 9 AM–12 PM and 3 PM–6 PM
    - Lowest activity: 3 AM–6 AM
  
## Conclusion
The Uber Cab Service Analysis project successfully provides a comprehensive view of operational efficiency, demand drivers, revenue patterns, and customer experience.

### Key Findings
- Auto & Bike dominate bookings and revenue.
- High cancellation rates require improvement in driver allotment and demand forecasting.
- Strong customer loyalty exists but can be improved by offering rewards.
- UPI remains the preferred payment option.
- Peak hours & top locations should guide fleet allocation to maximize revenue.

### Business Recommendations
- Optimize supply-demand matching in high-cancellation zones.
- Improve driver availability during peak hours.
- Promote underperforming categories (e.g., Uber XL) using discounts.
- Introduce loyalty programs for frequent riders.
- Strengthen driver incentives to enhance ratings & reduce cancellations.
  

