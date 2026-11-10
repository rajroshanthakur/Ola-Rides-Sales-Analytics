
# 🚗 Ola Rides Sales & Business Analytics | SQL & Power BI

## 📌 Project Overview

This project focuses on analyzing Ola's ride-booking data using SQL and Power BI to evaluate business performance, identify operational challenges, understand customer behavior, and uncover opportunities for business improvement.

An interactive Power BI dashboard was developed to transform raw booking data into meaningful business insights. The analysis focuses on ride completion, cancellations, revenue performance, vehicle categories, and customer and driver satisfaction.

**Analysis Period:** 1 July 2024 – 31 July 2024

---

## 📊 Business Performance Highlights

The following KPIs were identified from the actual Power BI dashboard:

| Key Performance Indicator | Actual Result |
|---|---:|
| Total Bookings | 103,024 |
| Successful Bookings | 63,967 |
| Cancelled Bookings | 39,057 |
| Booking Success Rate | 62.09% |
| Booking Cancellation Rate | 37.91% |

### 🔍 Key Performance Findings

- **62.09% Booking Success Rate:** Approximately 62 out of every 100 bookings were successfully completed.
- **37.91% Cancellation Rate:** Nearly 38 out of every 100 bookings were cancelled, highlighting a major operational challenge.
- **35.49% Driver Cancellation:** Personal and car-related issues represented the largest category of driver-side cancellations.
- **30.24% Customer Cancellation:** Drivers not moving towards pickup locations represented the largest category of customer-side cancellations.

**Business Opportunity:** Improving driver availability, pickup response time, and vehicle reliability could help increase successful bookings and reduce cancellations.

---

## 🎯 Business Problem

Ola's ride-booking operations involve a large volume of daily transactions. Monitoring booking performance, identifying cancellation reasons, and maintaining customer satisfaction are essential for operational efficiency.

The major business challenges addressed in this project include:

- High ride cancellation rates affecting booking completion.
- Difficulty identifying the major reasons behind customer and driver cancellations.
- Limited visibility into vehicle-wise performance and customer satisfaction.
- Driver availability and pickup coordination challenges.
- Need for better monitoring of customer and driver service quality.
- Difficulty converting raw transactional data into actionable business insights.

---

## 💡 Business Solution

To address these challenges, I performed SQL-based data analysis and developed an interactive Power BI dashboard.

The solution includes:

- Analyzed booking performance to identify successful and cancelled rides.
- Investigated customer-side and driver-side cancellation patterns.
- Compared customer and driver ratings across different vehicle categories.
- Developed interactive KPIs and visualizations for business performance monitoring.
- Identified operational improvement opportunities through data-driven analysis.

---

## 🚫 Ride Cancellation Analysis

### 1. Driver-Side Cancellation Analysis

| Cancellation Reason | Bookings | Percentage |
|---|---:|---:|
| Personal & Car Related Issues | 6.54K | 35.49% |
| Customer Related Issues | 5.41K | 29.36% |
| Customer Coughing / Sick | 3.65K | 19.82% |
| More Than Permitted People | 2.83K | 15.32% |

**Key Business Insights:**

- Personal and car-related issues accounted for the highest share of driver-side cancellations at **35.49%**.
- Customer-related issues contributed **29.36%**.
- Vehicle maintenance and driver readiness are important areas requiring attention.

### 2. Customer-Side Cancellation Analysis

| Cancellation Reason | Bookings | Percentage |
|---|---:|---:|
| Driver Is Not Moving Towards Pickup | 3.18K | 30.24% |
| Driver Asked to Cancel | 2.67K | 25.43% |
| Change of Plans | 2.08K | 19.82% |
| AC Is Not Working | 1.57K | 14.93% |
| Wrong Address | 1.01K | 9.57% |

**Key Business Insights:**

- **30.24%** of customer-side cancellations occurred because drivers were not moving towards pickup locations.
- **25.43%** were associated with drivers asking customers to cancel.
- Together, these two reasons represented **55.67%** of customer-side cancellations.
- Pickup coordination and driver communication are significant improvement areas.

---

## ⭐ Customer & Driver Ratings Analysis

The dashboard compares customer and driver satisfaction across seven vehicle categories.

### Vehicle-Wise Driver Ratings

| Vehicle Type | Driver Rating |
|---|---:|
| Prime Sedan | 3.99 |
| Prime SUV | 4.01 |
| Prime Plus | 4.00 |
| Mini | 3.99 |
| Auto | 4.00 |
| Bike | 3.98 |
| E-Bike | 4.01 |

### Vehicle-Wise Customer Ratings

| Vehicle Type | Customer Rating |
|---|---:|
| Prime Sedan | 4.00 |
| Prime SUV | 4.00 |
| Prime Plus | 4.01 |
| Mini | 4.00 |
| Auto | 4.00 |
| Bike | 3.99 |
| E-Bike | 3.99 |

### Rating Insights

- Prime SUV and E-Bike recorded the highest driver rating of **4.01**.
- Prime Plus achieved the highest customer rating of **4.01**.
- Bike recorded the lowest driver rating of **3.98**.
- Customer ratings remained consistent between **3.99 and 4.01** across vehicle categories.

**Business Finding:** Overall ratings indicate consistent service quality across vehicle categories, with opportunities for targeted service improvements.

---

## 🚀 Business Recommendations & Improvement Opportunities

Based on the actual dashboard findings, the following business improvements are recommended:

| Business Challenge | Recommended Improvement |
|---|---|
| High cancellation rate (37.91%) | Introduce cancellation monitoring and targeted reduction strategies. |
| Personal and car-related issues (35.49%) | Improve vehicle maintenance and driver readiness checks. |
| Driver not moving towards pickup (30.24%) | Monitor driver response time and improve pickup coordination. |
| Driver-requested cancellations (25.43%) | Strengthen driver accountability and cancellation policies. |
| AC-related cancellations (14.93%) | Introduce regular vehicle inspection and maintenance. |
| Lower Bike driver ratings (3.98) | Investigate feedback and provide targeted driver training. |

### Expected Business Benefits

- Increased successful ride completion rates.
- Reduced booking cancellations.
- Improved driver availability and vehicle reliability.
- Better customer experience and satisfaction.
- Improved operational efficiency.
- Greater revenue opportunities through completed rides.

*Note: These are proposed improvements and expected benefits, not measured post-implementation results.*

---

## 🛠️ Technical Skills & Tools Used

| Technology / Skill | Application |
|---|---|
| SQL (MySQL) | Data extraction, querying, filtering, aggregation, and analysis |
| Power BI | Interactive dashboard development and visualization |
| Power Query | Data cleaning and transformation |
| DAX | KPI calculations and analytical measures |
| Data Analysis | Identifying trends, patterns, and business insights |
| Data Visualization | Presenting analytical findings through charts and dashboards |
| Business Intelligence | Converting data into actionable recommendations |
| Excel / CSV | Data handling and source data management |

---

## 📈 Dashboard Features

The project includes interactive dashboard sections:

1. **Overall Analysis:** High-level booking performance and business KPIs.
2. **Vehicle Type Analysis:** Comparison of vehicle categories and ride performance.
3. **Revenue Analysis:** Analysis of booking value and revenue trends.
4. **Cancellation Analysis:** Driver-side and customer-side cancellation reasons.
5. **Ratings Analysis:** Vehicle-wise customer and driver satisfaction.

---

## 🔮 Future Enhancements

- Implement machine learning models for ride demand forecasting.
- Develop predictive models to identify potential ride cancellations.
- Integrate real-time data for continuous performance monitoring.
- Add geographical analysis to identify high-demand pickup locations.
- Develop automated alerts for increasing cancellation rates.

---

## 🔗 Live Power BI Dashboard

Explore the interactive dashboard:

[**View Ola Rides Sales Analytics Dashboard**](https://app.powerbi.com/view?r=eyJrIjoiNjZjYTAzNzQtMDY5Zi00YWRkLTlkM2UtZGFlNWIyZTljMzU2IiwidCI6Ijk5ZTNiZmM3LWI4ZTAtNDc1Zi1hNGU2LTM5ODQyZjY5YjhkZSJ9)

---

## 👨‍💻 Author

**Raj Thakur**

Aspiring Data Analyst | Data Science Enthusiast

**Technical Skills:** SQL | Power BI | Python | Excel | Data Analysis | Data Visualization | Business Intelligence

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback!

