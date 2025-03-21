Revenue Insights in Hospitality Domain (Power BI Project)
📁 Project Description
This Power BI project, "Revenue Insights in Hospitality Domain", focuses on exploring and analyzing the revenue metrics of a hotel chain. The dashboard is designed to help stakeholders gain actionable insights into various KPIs such as Occupancy Rate, ADR (Average Daily Rate), RevPAR (Revenue Per Available Room), and overall booking trends.

The project utilizes dimensional data modeling (star schema) principles, loading multiple fact and dimension tables to create a rich, interactive dashboard aimed at driving better business decisions.

🚀 Files Included
File Name	Description
Revenue Insights in Hospitality Domain.pbix	Power BI report file containing the complete dashboard.
metrics list.xlsx	Contains the KPIs and metrics tracked in the dashboard.
dim_date.csv	Date dimension table.
dim_hotels.csv	Hotel dimension table with hotel-related attributes.
dim_rooms.csv	Room dimension table with room types and capacities.
fact_bookings.csv	Booking fact table with individual transaction records.
fact_aggregated_bookings.csv	Aggregated bookings data for performance comparison.
📈 Key Metrics Visualized
Occupancy Rate
Average Daily Rate (ADR)
Revenue Per Available Room (RevPAR)
Total Revenue
Room Type Revenue Contribution
Hotel-wise Performance
Monthly and Seasonal Booking Trends
🗂 Data Model Overview
The data is structured using a star schema:

Fact Tables: fact_bookings, fact_aggregated_bookings
Dimension Tables: dim_date, dim_hotels, dim_rooms
Relationships are built in Power BI to enable filtering, aggregation, and drill-through analysis.

🎯 Purpose & Use Cases
Analyze booking and revenue trends in the hospitality domain
Identify top-performing hotels and room types
Support decision-making for pricing strategies and marketing campaigns
Forecast demand based on historical trends
💻 How to Use
Clone or download the repository.
Open the .pbix file in Power BI Desktop.
Review the data model and explore the interactive dashboard.
Modify visuals or add new metrics as per your business requirements.
📚 Skills & Tools Utilized
Power BI Desktop
Data Modeling (Star Schema)
DAX (Data Analysis Expressions)
CSV Data Cleaning & Transformation
Interactive Dashboard Design
KPI Metrics Calculation
📌 Future Improvements
Integrate dynamic forecasting for future bookings
Add hotel location mapping using Power BI maps
Enable real-time data refresh from a database or cloud source
Include sentiment analysis from customer reviews
