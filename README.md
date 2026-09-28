## Supply Chain Analytics Dashboard

An end-to-end data analysis project exploring delivery delays and their business impact across 180,000+ orders — built with Python for analysis and Power BI for an interactive, 
decision-ready dashboard.

## Purpose

This project analyzes order-level supply chain data to identify why deliveries are getting delayed, which factors are driving those delays the most, 
and what financial impact they have — then presents the findings through an interactive 3-page Power BI dashboard.

## Tech Stack

The project was built using the following tools and technologies:

1. Python (Pandas, NumPy) — Data cleaning, transformation, and feature engineering

2. Matplotlib & Seaborn — Exploratory data visualization

3. PowerBI Desktop — Main dashboard/report creation

4. DAX (Data Analysis Expressions) — Custom measures for delay %, profit, and loss calculations

5. File Format — .ipynb for the Python notebook, .pbix for the Power BI dashboard, .png for dashboard preview screenshots

## Data Source

The dataset contains supply chain and order-level data, including order dates, shipping mode, customer segment, product category, region, delivery status,
and profit per order — covering 180,519 orders in total.

## Features / Highlights

1. Business Problem

Late deliveries directly hurt customer satisfaction and profitability, but without analysis it's unclear which part of the supply chain is actually causing the delays —
is it the shipping method, the region, the product category, or something else? This project was built to answer that question with data instead of guesswork.

2. Goal of the Dashboard

To give a clear, at-a-glance view of overall delivery performance, and to pinpoint the exact factors causing the most delays — so the business knows where to focus first.
Walkthrough of Key Visuals

Page 1 (Overview): KPI cards for Total Orders, Delay %, On-Time %, Total Profit, and Delay Loss, along with a Top 10 Delay Drivers chart that ranks the single biggest contributors to delay across shipping mode, region, and 

Page 2 (Detailed Analysis): A breakdown of delay % across Product Category, Order Region, Customer Segment, and Shipping Mode

Page 3 (Key Findings & Recommendations): A summary of the most important findings, ranked by priority, along with clear next-step recommendations

## Business Impact & Insights

1. Out of 180,519 orders, 57% were delayed, resulting in an estimated ₹2.23M loss

2. First Class shipping had a 100% delay rate — every order shipped this way was late, making it the single biggest bottleneck

3. Second Class shipping followed closely at around 80% delay

4. The Golf Bags & Carts category and the Central Africa region both showed delay rates above 60%

5. Customer segment (Consumer, Corporate, Home Office) showed almost no variation in delay rate, pointing to shipping and logistics — not customer type — as the real driver of delays

## Recommendations

1. Audit the carriers/partners handling First and Second Class shipping immediately, since they account for most of the delay problem

2. Review logistics infrastructure specifically for the Central Africa region

3. Review the fulfillment process for the Golf Bags & Carts category

4. study the Standard Class shipping process, which has the lowest delay rate, and apply its practices to other shipping modes


