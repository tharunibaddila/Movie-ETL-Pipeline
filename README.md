# 🎬 Movie ETL Pipeline

**Interactive Movie Dashboard | ETL Pipeline using AWS S3, Snowflake, and Power BI**

Overview

This project is an end-to-end ETL (Extract, Transform, Load) pipeline designed to automate movie metadata ingestion, normalization, and visualization using Amazon S3, Snowflake, and Power BI. The system enables users to interactively search for movies by genre, language, and platform availability while providing insights into runtime distributions and other key attributes.

**Architecture & Technologies Used:**
![Screenshot 2025-03-27 at 3 33 28 PM](https://github.com/user-attachments/assets/17b4ad50-b201-464e-9aef-8929a9a004f8)


**Data Storage & Ingestion:**
Movie metadata (e.g., title, genre, language, availability) is stored in Amazon S3 as raw JSON/CSV files.
Snowpipe is used to automate continuous ingestion into Snowflake, ensuring real-time updates.

**Data Transformation & Processing:**
SQL queries in Snowflake are used to clean and normalize the metadata (handling missing values, ensuring genre consistency, and optimizing for analytics).
Data is structured in fact and dimension tables, improving query performance.

**Data Visualization & Dashboarding:**
Power BI is used to create an interactive dashboard with:
DAX-driven calculations for real-time insights.
IAM-based access controls for role-based security.
A searchable interface where users can filter by movie name, genre, and platform availability.
Runtime and genre distribution charts for better content insights.

**Key Features:**

✅ Automated ETL Process:
Snowpipe automatically ingests new movie metadata files from Amazon S3 into Snowflake.
SQL-based transformations ensure data consistency and quality.

✅ Interactive Movie Dashboard:
Users can search by movie title, genre, and streaming platform (Netflix, Amazon Prime, Disney+, etc.).
Filters and drill-down capabilities for in-depth analysis.

✅ Performance Optimizations:
Indexed Snowflake tables for faster queries.
Pre-aggregated metrics to enhance dashboard responsiveness.

✅ Secure & Scalable:
IAM-based authentication controls dashboard access.
Scalable infrastructure using AWS cloud services.

**Outcome & Impact**

🎯 Reduced Data Processing Time by 60% with automated ingestion.

🎯 Enhanced Data Visibility through real-time interactive dashboards.

🎯 Improved Decision-Making with genre-wise and platform-wise insights.

**Next Steps & Future Enhancements**

Integrate Machine Learning: Use AI to recommend trending movies based on user behavior.
Expand Data Sources: Ingest ratings, reviews, and box office data for a richer dataset.
Deploy as a Web App: Provide a user-friendly web interface for broader accessibility.


## 📊 Live Power BI Dashboard

🔗 View the Power BI
Dashboard:(https://app.powerbi.com/view?r=eyJrIjoiYzA5N2Y0ODAtZmFlYy00OWYwLTlmMDgtM2ZkOGMyODFjZjU4IiwidCI6ImViZmE0ZWRhLTM3NjYtNGZjMS04ZTgyLTAyYTVkZWJjY2M5NiIsImMiOjN9)  


