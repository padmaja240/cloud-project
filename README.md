Overview
This project is a cloud-integrated data analytics system designed to analyze customer behavior using Azure services, Python analytics, and Power BI dashboards.

The system follows an end-to-end pipeline:

Data Storage (Azure Blob Storage)
ETL Processing (Azure Data Factory)
Structured Storage (Azure SQL Database)
Data Analysis (Google Colab - Python)
Visualization (Power BI)
Objectives
Analyze customer activity patterns
Identify peak engagement times
Perform customer segmentation using RFM analysis
Build interactive dashboards for business insights
Architecture
Raw Data → Azure Blob Storage → Azure Data Factory (ETL) → Azure SQL Database → Google Colab (Analytics) → Power BI (Visualization)

Tech Stack
Cloud (Azure)
Azure Blob Storage → Raw data storage
Azure Data Factory → ETL pipeline (data cleaning & transformation)
Azure SQL Database → Structured data storage
Analytics
Google Colab (Python)
Pandas
NumPy
Matplotlib / Seaborn
Visualization
Power BI (connected to Azure SQL Database)
⚙️ Implementation Details
1️⃣ Data Storage (Azure Blob Storage)
Uploaded raw customer datasets
Acts as the initial data lake layer
2️⃣ ETL Pipeline (Azure Data Factory)
Extract → Raw data from Blob Storage
Transform → Data cleaning, formatting
Load → Insert into Azure SQL Database
3️⃣ Database (Azure SQL Database)
Structured tables created for:
Customer data
Transaction data
Optimized for querying and analytics
4️⃣ Data Analysis (Google Colab)
📌 Time-Based Analytics
Analyzed customer activity based on:
Hour of the day
Peak traffic times
Identified when most customers interact with the system
📌 Customer Behaviour Analysis
Purchase patterns
Visit frequency
Trend identification
📌 RFM Analysis
Recency → How recently a customer made a purchase
Frequency → How often they purchase
Monetary → How much they spend
Used RFM to:

Segment customers
Identify high-value customers
Detect inactive users
5️⃣ Visualization (Power BI)
Connected directly to Azure SQL Database
Created dashboards showing:
Customer trends
Peak usage time
RFM segments
Interactive filtering and drill-down analysis
📂 Project Structure
├── Documentations and Presentations
│   ├── Project PPT
│   ├── Abstract
│   ├── Documentation
│
├── Implementation
│   ├── Azure (Screenshots)
│   ├── Google Colab (Notebook)
│   ├── PowerBI (Screenshots)
│
└── README.md
Key Insights
Identified peak customer activity hours
Segmented customers into valuable groups using RFM
Enabled data-driven decision-making through dashboards
Screenshots
(Include screenshots in respective folders)

Azure resources setup
ETL pipeline
Power BI dashboards
Future Enhancements
Real-time data streaming using Azure Event Hub
Machine Learning models for customer prediction
Automated alert system for business insights
License
This project is for educational purposes.

About
A scalable cloud-based analytics system using Microsoft Azure for data storage, ETL, and database management. It processes raw customer data, applies Python-based analytics in Google Colab, and performs RFM and time-based analysis. Insights are visualized through interactive Power BI dashboards for decision-making.

Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 0 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Contributors
1

Languages
Jupyter Notebook
100.0%
Footer
