Overview:
Comprehensive data warehousing and analytics solution for NYC Taxi & Limousine Commission trip data, implementing a cloud-based ETL pipeline to analyze urban mobility patterns and optimize transportation services. Built a star schema data model processing January 2022 taxi trip data with integrated geospatial analysis.
Technical Architecture:

Data Pipeline: AWS-based ETL using S3, Glue, Athena, and Lambda for automated processing
Data Sources: Yellow taxi trip data (2022-01) and NYC taxi zone lookup tables
Schema Design: Star schema with 5 dimension tables (pickup/dropoff locations, time, rate codes, payment types) and central fact table
Automation: Lambda-triggered pipeline with Glue Crawler for schema discovery and metadata management

Key Results:

Revenue Analysis: $2.2M total revenue with peak demand during 6 PM commute hours
Geographic Insights: Manhattan dominates trip density, particularly around Times Square and business districts
Payment Trends: 79.6% credit card adoption showing shift toward digital transactions
Operational Metrics: 2.7 mile average trip distance with major hotspots at JFK/LaGuardia airports

Technical Innovation:

Serverless OLAP architecture enabling real-time querying of large datasets
Interactive Looker Studio dashboards with geospatial mapping and filtering capabilities
Automated ETL workflow with error handling and monitoring

Technologies Used:
AWS (S3, Glue, Athena, Lambda), Python, SQL, Looker Studio, star schema design
This project demonstrates expertise in cloud data engineering, ETL pipeline design, and transportation analytics with actionable business insights for urban mobility optimization.
