# 📦 Amazon-delivery-Data-Analysis-Project


## 🚀 Project Vision & Objective

In today’s fast-paced e-commerce landscape, **delivery speed and customer satisfaction** are critical for success. This project analyzes **Amazon delivery operations** using real-world data to uncover patterns, identify bottlenecks, and provide actionable insights for improving **operational efficiency and customer experience.**

By leveraging **Python, Pandas, NumPy, and visualization tools**, the project examines **delivery speed, traffic and weather impact, agent performance, and area-specific challenges** to support **data-driven decisions** for last-mile delivery optimization.

## 🧩 Business Problems Addressed

### 🔴 Delivery Delays
Orders often take longer than expected, negatively affecting customer satisfaction.

### 🔴 Traffic & Weather Impact
Unpredictable weather and traffic conditions slow down deliveries and reduce efficiency.

### 🔴 Agent Performance Variability
Delivery performance differs based on agent age, experience, and vehicle type, creating inconsistencies.

## 🔴 Peak-Time Resource Allocation
High-volume periods lead to congestion and longer delivery times, requiring better planning.

## 🏗️ Technical Approach

**Python & Pandas** – for data cleaning, processing, and analysis
**NumPy** – for numerical calculations
**Matplotlib & Seaborn** – for visualization and trend analysis
**Haversine Formula** – to calculate geographic distances between pickup and drop-off points

## Data Flow:

1- Clean and preprocess dataset (handle missing values, correct timestamps, rename columns)

2- Calculate new metrics: **pickup_delay_minutes, total_delivery_time, distance_km**

3- Segment data by weather, traffic, time-of-day, area, agent age, and vehicle type

4- Analyze key performance indicators (delivery speed, ratings, volume, delays)

5- Visualize insights and identify operational recommendations

## 📈 Key Insights

✅ **Average Delivery Distance:** 9.73 km

✅ **Average Customer Rating:** 4.64 / 5

✅ **Peak Days:** Wednesday & Friday have highest order volumes

✅ **Best Delivery Time Range:** 60–120 minutes yields highest customer satisfaction

✅ **Area Analysis:**

- Metropolitan: busiest, slightly longer deliveries

- Urban & Other: faster deliveries, higher ratings

- Semi-Urban: slowest deliveries, lower ratings

✅ **Vehicle Performance:**

- Scooters excel in traffic-heavy areas

- Vans perform better in urban bulk deliveries

✅ **Agent Age Insights:**

- 20–30 years: faster deliveries, slightly higher ratings

- 30–40 years: handles more orders, uses more vans

## 🧪 Diagnostics & Root Cause Analysis

🔹 **Lower Ratings:** Long delivery times, bad weather, semi-urban infrastructure

🔹 **Pickup Delays:** Mostly 5–15 minutes; occasional midnight log issues

🔹 **Evening Drops:** Higher traffic and accumulated delays affect performance

🔹 **Agent Variability:** Age, vehicle choice, time-of-day, and experience contribute to performance differences

## 🚀 Recommendations

1- Increase agent allocation during peak hours

2- Use scooters in traffic-heavy or narrow-street zones

3- Assign younger agents to time-sensitive orders

4- Deploy experienced agents for bulk deliveries or complex routes

5- Integrate real-time weather and traffic data for planning

6- Reduce pickup delays with smarter dispatching

7- Prepare for high-demand days with optimized scheduling

8- Collect and analyze qualitative customer feedback
