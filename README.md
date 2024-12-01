# PDM Project: Well and Production Data Analysis
This project involves data analysis and visualization of oil and gas production and well data. The goal is to explore, process, and extract meaningful insights using Python, pandas, and visualization libraries.

### Project Objectives
 - Write well-commented Python code.
 - Manipulate and analyze data using pandas.
 - Work with databases like SQLite and PostgreSQL.

### Datasets
Norway Wellbores:

Stored in a SQLite database (wells_data.db, table wells_data).
Volve Production Data:

Provided as an Excel file (Volve_production_data.xlsx) with two tabs:
Daily Production Data
Monthly Production Data
Key Features
Data Exploration

Load and explore well and production datasets.
Handle multi-tab Excel files and databases.
Database Operations

Convert SQLite database to an Excel file and import it into a new SQLite or PostgreSQL database.
Well Data Visualization

Scatter plots for bottom hole temperature vs. depth and drilling days vs. depth.
Calculate and display average total depth grouped by "Age At Td".
Production Data Analysis

Monthly oil, gas, and water production trends for specific wellbores.
Aggregate oil production by wellbore.
Merged Data Analysis

Merge well data and production data for deeper insights.
Analyze the correlation between total depth and oil production.
Technologies Used
Python: pandas, seaborn, matplotlib, sqlite3.
Databases: SQLite, PostgreSQL.
Data Visualization: seaborn, matplotlib.
