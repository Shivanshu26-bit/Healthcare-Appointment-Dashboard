\# Healthcare Appointment Dashboard



A healthcare appointment analysis project built using SQL, data cleaning, data transformation, and Tableau Public.



\## Project Overview



This project analyzes healthcare appointment data to understand appointment trends, completion status, cancellations, no-shows, specialization-wise appointments, and city-wise appointment distribution.



The final result is an interactive Tableau dashboard designed to make the appointment data easier to understand through KPIs and visualizations.



\## Data Pipeline



The project follows a Bronze → Silver → Gold data pipeline.



\### Bronze Layer



The Bronze layer contains the raw/source data:



\- Patients

\- Doctors

\- Appointments

\- Billing



The raw data is preserved as the starting point for the transformation process.



\### Silver Layer



The Silver layer contains cleaned and structured data prepared for analysis.



Examples include:



\- `Silver\_Appointments`

\- `Silver\_Billing`



The cleaning/transformation process prepares the source data for consistent analysis and reporting.



\### Gold Layer



The Gold layer contains analysis-ready and summarized data:



\- `Gold\_Summary`

\- `Gold\_Daily`

\- `Gold\_Specialization`

\- `Gold\_Billing`



These tables are designed to support reporting and dashboard visualizations.



\## Tableau-Ready Data



The final Tableau analysis uses the `Tableau\_Ready` dataset.



The dataset contains \*\*298 appointments\*\*.



\### Appointment Summary



| Metric | Count |

|---|---:|

| Total Appointments | 298 |

| Completed | 218 |

| Cancelled | 57 |

| No-show | 23 |



\## Dashboard Visualizations



The Tableau dashboard contains:



\- Total Appointments KPI

\- Completed Appointments KPI

\- Cancelled Appointments KPI

\- No-show Appointments KPI

\- Daily Appointment Trend

\- Specialization Comparison

\- City Comparison



\### Specialization Analysis



The dashboard compares appointment counts across available specializations such as:



\- Cardiology

\- Dermatology

\- General Medicine

\- Orthopedics

\- Pediatrics



Null specialization values were excluded from this particular visualization.



\### City Analysis



The dashboard also compares appointment counts across available cities including:



\- Delhi

\- Faridabad

\- Gurugram

\- Rewari



Null city values were excluded from this particular visualization.



\## Data Cleaning and Transformation



The data preparation process included:



1\. Organizing the source data into separate entities.

2\. Creating the Bronze layer from the raw data.

3\. Cleaning and structuring appointment and billing data in the Silver layer.

4\. Creating summarized Gold-layer tables for analysis.

5\. Preparing a Tableau-ready dataset.

6\. Handling missing/null values during visualization.

7\. Creating aggregated metrics required for the dashboard.

8\. Connecting the final dataset to Tableau Public.



\## Technologies Used



\- SQL

\- Microsoft Excel

\- Tableau Public

\- Git

\- GitHub



\## Project Files



\### SQL



\- `01\_create\_tables.sql` — database/table creation

\- `03\_bronze\_to\_silver\_to\_gold.sql` — Bronze, Silver and Gold transformation process



\### Tableau



\- `Healthcare\_Appointment\_Dashboard.twbx` — Tableau workbook



\### Dataset



\- `KRMU\_Tableau\_Ready\_Data.xlsx` — prepared dataset used for analysis



\## Tableau Dashboard



The final dashboard was created using Tableau Public and provides an overview of healthcare appointment activity through interactive visualizations and KPIs.



\## Repository



GitHub: `Shivanshu26-bit/Healthcare-Appointment-Dashboard`



\## Author



\*\*Shivanshu Shukla\*\*



BCA — Artificial Intelligence \& Data Science

