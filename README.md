# world-bank-health-expenditure-dashboard
🌍 World Bank Health Expenditure Dashboard
Project Overview

This project analyzes World Bank health expenditure data to identify patterns across regions, income groups, countries, and time. Using Microsoft Excel, Power Query, and Power Pivot, I transformed raw World Bank data into a relational data model and developed an interactive dashboard to support exploratory analysis and data-driven decision making.

Business Questions

This project was designed to answer the following questions:

Which world regions have the highest average health expenditure per capita?
How has health expenditure changed over time?
How do spending patterns differ across income levels?
Which countries report the highest average health expenditures?
Tools & Technologies
Microsoft Excel
Power Query
Power Pivot
Excel Data Model
PivotTables
PivotCharts
Slicers
Data Source

Source: World Bank Open Data

Dataset: Health expenditure per capita (current US$)

https://data.worldbank.org/indicator/SH.XPD.CHEX.GD.ZS

Data Preparation (ETL Process)

The raw dataset required extensive transformation before analysis.

The data preparation workflow included:

Importing raw CSV files into Power Query
Removing unnecessary rows and columns
Promoting headers
Correcting data types
Merging country metadata
Expanding Region and Income Level fields
Unpivoting yearly columns into a normalized structure
Creating Fact and Dimension tables
Building a relational data model using Country Code
Creating PivotTables and PivotCharts for analysis
Dashboard Features

The dashboard includes:

Regional comparison of average health expenditure
Health expenditure trends over time
Income level comparisons
Country-level exploration
Interactive slicers for Year, Region, and Income Level

<img width="1704" height="767" alt="image" src="https://github.com/user-attachments/assets/b4baa313-5ea7-4b59-8c0b-9f37ebb52709" />
<img width="808" height="465" alt="image" src="https://github.com/user-attachments/assets/147b0d8b-d8f8-4d69-9519-306cc4e363c2" />
<img width="799" height="444" alt="image" src="https://github.com/user-attachments/assets/5c13bf62-e5be-4daa-a889-fa5a9876f157" />
<img width="802" height="460" alt="image" src="https://github.com/user-attachments/assets/97194067-3b8d-4084-922a-c5b8ca888419" />


Key Findings

Preliminary analysis revealed several notable trends:

North America reported the highest average health expenditure per capita.
Sub-Saharan Africa reported the lowest average expenditure.
Higher-income regions consistently demonstrated greater healthcare spending.
Regional differences in healthcare investment are substantial and easily explored using interactive filters.



Challenges Encountered

One of the most valuable aspects of this project was troubleshooting multiple technical challenges encountered during the ETL process. These included:

CSV import inconsistencies
Metadata merge errors
Power Query transformation issues
Data loading failures
Data Model relationship configuration
Query dependency troubleshooting

Resolving these issues required iterative testing, restructuring query steps, and validating relationships before building the final dashboard.

Skills Demonstrated
ETL (Extract, Transform, Load)
Data Cleaning
Data Transformation
Data Modeling
Relational Data Modeling
Exploratory Data Analysis (EDA)
Dashboard Development
Data Visualization
Excel Power Query
Power Pivot
Data Storytelling
Future Enhancements



Ideas include:

Incorporate additional World Bank health indicators.
Add KPI cards for global averages and regional comparisons.
Build a dynamic dashboard with additional slicers.
Expand analysis using Power BI.
Repository Structure
📁 World-Bank-Health-Expenditure-Dashboard
│
├── README.md
├── World_Bank_Health_Dashboard.xlsx
├── screenshots/
│   ├── dashboard.png
│   ├── power_query.png
│   ├── data_model.png
│   ├── pivot_table.png
│   └── dashboard_overview.png
└── data/
    └── source_information.txt
    
Lessons Learned

This project reinforced the importance of designing a strong data model before building visualizations. Transforming wide-format data into a normalized fact table, creating a separate country dimension, and establishing relationships in the Data Model significantly simplified analysis. Throughout development, I also gained experience troubleshooting Power Query transformations, resolving data loading issues, and validating relationships before creating dashboards. The project demonstrated that effective analytics depends as much on careful data preparation and problem solving as it does on visualization.

About This Project:

This project was completed as part of my transition from a 17-year career as a registered nurse into data analytics. It reflects my commitment to learning industry-standard data preparation, modeling, and visualization techniques using real-world public datasets.
