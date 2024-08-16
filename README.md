# Oktoberfest_Beer_and_Chicken_Trends

## Oktoberfest Chicken and Beer Price Analysis
### Problem Statement
The primary objective of this repository is to analyze and visualize the trends in chicken and beer prices at Oktoberfest over a span of years. By leveraging the power of Power BI, the dashboard provides insights into price variations, helping stakeholders understand the economic factors influencing these key Oktoberfest commodities.

### Challenges Faced
- Data Availability: Sourcing accurate and consistent data across multiple years posed a significant challenge. Ensuring the reliability of historical data was critical.
- Data Quality: The data contained missing values, inconsistencies in units (e.g., different currencies), and outliers that could skew the analysis.
- ETL Process: Efficiently extracting, transforming, and loading (ETL) the data required careful planning, given the need to integrate data from various sources.
- Visual Representation: Developing a dashboard that conveys the complex pricing trends in an intuitive and user-friendly manner was essential.

### Key Performance Indicators (KPIs)
- Average Price of Chicken: Monitors the annual average cost of chicken at Oktoberfest.
- Average Price of Beer: Tracks the yearly changes in beer prices.
- Average Chicken consumed in Kgs
- Average guests visited daily
- Average Beer consumed in Liters

### ETL Process
- Extraction: Data was sourced from multiple publicly available datasets, including historical price records, economic reports, and Oktoberfest archives.
- Transformation: Removed duplicate records, handled missing values by imputing where appropriate, and standardized currency units to a common format.
- Feature Engineering: Created new fields, such as conversion of hecto liters to liters and multiplying the millions to enrich the analysis.
- Loading: The cleaned and transformed data was loaded into Power BI for visualization. The data model was optimized to ensure efficient querying and real-time data updates.

### Conclusion
This Power BI dashboard offers a comprehensive analysis of Oktoberfest chicken and beer prices, showcasing significant trends and patterns. It serves as a valuable tool for festival organizers, vendors, and enthusiasts, providing data-driven insights to inform pricing strategies and understand market dynamics over time.

Explore the dashboard to dive deeper into the pricing trends and make informed decisions for future Oktoberfest celebrations.
