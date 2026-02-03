# 🚗 Uber Ride Analytics Dashboard

**Interactive Power BI Analysis for Ride Performance & Revenue
Optimization**

This project presents an **interactive Power BI dashboard** that
delivers comprehensive insights into **Uber ride performance, revenue
trends, customer behavior, vehicle utilization, and location-based
demand**. The dashboard enables data-driven decision-making to improve
operational efficiency and profitability.


## 📌 Business Objective

The primary goal of this project is to transform raw ride data into
actionable insights by:

-   Gaining visibility into **booking performance and revenue trends**
-   Understanding **ride cancellations and lost bookings**
-   Evaluating **vehicle-wise performance** to optimize fleet
    composition
-   Analyzing **customer behavior and retention**
-   Identifying **high-demand locations** for strategic driver
    deployment


## 📊 Dataset Overview

-   **93K** Completed Bookings\
-   **57K** Lost Bookings (Cancelled / Incomplete)\
-   **\$52M** Total Revenue\
-   **2.51M** Total Distance Covered\
-   **24.64 km** Average Distance per Ride\
-   **104K** Total Customers


## 🧹 Data Preparation & Modeling

### Data Cleaning & Transformation

-   Standardized booking, customer, vehicle, and payment data\
-   Removed duplicate records for accurate KPIs\
-   Segmented completed vs cancelled rides\
-   Created date hierarchies for monthly and quarterly trends\
-   Validated revenue, distance, and booking metrics

### Data Model

-   **Star Schema Architecture**
    -   Fact Table: Bookings\
    -   Dimensions: Customers, Vehicles, Payment Methods, Calendar

### DAX Measures

-   Completed & Lost Bookings\
-   Total & Average Revenue per Ride\
-   Total & Average Distance\
-   Dynamic Month & Quarter filtering
-   

## 📈 Dashboard Pages & KPIs

### Overview

-   Completed & Lost Bookings\
-   Total Revenue\
-   Total Distance Covered\
-   Average Ride Distance

### Vehicle Analysis

-   Revenue by vehicle type\
-   Utilization performance comparison

### Revenue Intelligence

-   Revenue by payment method\
-   Trend analysis over time

### Rider Insights

-   Customer segmentation (First-time, Return, Regular riders)\
-   Customer & driver ratings

### Location Analytics

-   High-demand zones and operational hotspot
-   

## 🔍 Key Insights

-   Stable monthly completed bookings (**7K--8K**)\
-   **Auto and Bike** generate the highest revenue\
-   **UPI and Cash** are dominant payment methods\
-   Average customer rating: **4.40**\
-   Average driver rating: **4.23**\
-   **Khandsa** and **Ashram** are top booking locations

------------------------------------------------------------------------

## 💡 Actionable Recommendations

-   Optimize fleet mix toward high-performing vehicle types\
-   Reduce revenue loss from cancelled and incomplete rides\
-   Encourage digital payments to improve efficiency\
-   Improve driver availability in high-demand locations

------------------------------------------------------------------------

## 🚀 Conclusion & Future Enhancements

This dashboard provides a comprehensive analytical view of Uber ride
operations, enabling faster, data-driven decisions.

### Future Scope

-   Cancellation reason analysis\
-   Time-based demand forecasting\
-   Driver performance scorecards\
-   ML-based predictive analytics

------------------------------------------------------------------------

## 🛠 Tools & Technologies

-   Power BI\
-   DAX\
-   Excel
