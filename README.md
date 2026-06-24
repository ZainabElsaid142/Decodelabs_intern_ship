# E-Commerce Growth Tracker - Comprehensive Project Documentation

## Project Overview
Welcome to the E-Commerce Growth Tracker project! This repository serves as a comprehensive analytical framework designed for the DecodeLabs internship program. The primary objective of this project is to transform complex, raw e-commerce datasets into a structured, interactive, and high-impact business intelligence dashboard. 

In today’s data-driven market, the ability to translate raw transactional data into actionable insights is paramount. This project demonstrates proficiency in the entire data lifecycle—from ingestion and rigorous cleaning to sophisticated analysis and professional-grade visualization. By leveraging advanced features within Microsoft Excel, this tracker provides a robust solution for monitoring business health, identifying consumer trends, and optimizing strategic decision-making.

## Dashboard Overview: "E_COMMERCE GROWTH TRACKER"
<img width="646" height="326" alt="لقطة الشاشة 2026-06-24 225545" src="https://github.com/user-attachments/assets/3d9064e3-198b-4145-ab12-4615d5318a44" />

The dashboard is meticulously crafted to serve as a single source of truth for business performance. It features a modern, clean, and intuitive UI that allows stakeholders to navigate complex metrics with ease. The visual architecture includes:

* **Revenue Performance (Bar Chart):** A detailed breakdown of product revenue. This visualization identifies high-performing categories versus underperformers, enabling targeted inventory and marketing management.
* **Historical Sales Trends (Line Chart):** An advanced longitudinal analysis spanning 2023–2025. This visual representation maps quarterly sales trajectories, helping to identify seasonal cycles, growth plateaus, and long-term revenue momentum.
* **Promotional Efficacy (Donut Chart):** An analytical view of coupon code performance. By visualizing which marketing incentives drive the most sales, this chart quantifies the ROI of discount strategies.
* **Order Lifecycle Management (Donut Chart):** An end-to-end view of the order fulfillment process. It categorizes orders into 'Delivered', 'Pending', 'Cancelled', 'Returned', and 'Shipped', serving as a diagnostic tool for logistics and customer service efficiency.
* **Customer Payment Behavior (Donut Chart):** A segmentation of payment methods, illustrating how customers prefer to transact (e.g., Cash, Credit, Debit, Gift Cards). This is critical for optimizing checkout UX and financial planning.

**Interactive Filtering:** The dashboard is equipped with four dynamic, synchronized Slicers. These act as global filters, allowing users to instantly drill down into specific quarters, years, payment methods, or coupon campaigns, ensuring that the insights remain relevant and focused regardless of the data scale.

## Methodological Framework
The project's success is rooted in a disciplined, three-stage technical process:

### 1. Data Ingestion & Transformation (Power Query)
Data integrity is the foundation of this project. Using **Power Query (M language engine)**, the raw data underwent a stringent ETL (Extract, Transform, Load) process:
* **Sanitization:** Elimination of null values and inconsistent records.
* **Filtering:** Removal of extraneous bottom-row summary data to prevent calculation errors.
* **Structuring:** Ensuring data types (Date, Currency, Text) were correctly assigned for pivot analysis.

### 2. Analytical Modeling (Pivot Tables)
The backbone of the dashboard is a series of five optimized **Pivot Tables**. These tables aggregate thousands of individual transaction rows into meaningful KPIs, establishing a dynamic connection between raw inputs and visual outputs. By using "Show Values As" calculations, the project provides both absolute values and relative percentages, offering a nuanced perspective on performance metrics.

### 3. Visual Storytelling (Data Visualization)
The design philosophy emphasizes *clarity and impact*. By removing visual clutter (such as unnecessary fills and borders) and employing a professional, cohesive color palette, the dashboard shifts the focus entirely to the data. This design ensures that key stakeholders can grasp performance indicators at a single glance, turning static numbers into a narrative of growth and operational success.

---
*Developed as part of the DecodeLabs internship program to showcase data engineering and business intelligence expertise.*
