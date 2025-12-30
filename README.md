📋 Overview
This end-to-end data analytics project focuses on extracting actionable insights. The pipeline covers the entire data lifecycle: from initial data ingestion and cleaning in Python, deep-dive analysis using SQL, to interactive storytelling via Power BI and automated presentations with Gamma.

The goal of this project is to to analyze customer behavior to improve customer satisfaction and business performance.

📊 Dataset
Source: GitHub

Description: The dataset contains 3,900 rows and 18 columns, including customer demographics, purchase details, shopping behavior.

Format: CSV.

🛠️ Tools & Technologies
Programming: Python (Pandas, Numpy, Matplotlib/Seaborn)

Database: SQL

Visualization: Power BI

Reporting: Gamma AI (Presentation), Microsoft Word (Documentation)

Environment: Jupyter Notebook

🚀 Project Steps
1. Data Ingestion & EDA (Python)
Loaded raw data using Pandas.

Performed Exploratory Data Analysis (EDA) to identify missing values, outliers, and distributions.

Cleaned and pre-processed data (handled nulls, corrected data types) to ensure high data quality for SQL migration.

2. Database Management (SQL)
Imported the cleaned dataset into a relational database.

Wrote complex SQL queries (using Joins, CTEs, and Window Functions) to aggregate metrics such as [mention a metric, e.g., Monthly Recurring Revenue].

3. Data Visualization (Power BI)
Connected Power BI to the SQL database.

4. Reporting & Presentation
Synthesized findings into a formal written report.

Leveraged Gamma AI to generate a professional slide deck for stakeholders, highlighting key takeaways and recommendations.

📈 Dashboard Preview
<img width="1655" height="915" alt="image" src="https://github.com/user-attachments/assets/5605bf95-9b9c-4157-ba8a-391b17df0185" />

💡 Key Results & Insights
Insight 1: Discovered that male customers generated significantly more revenue than female customers.

Insight 2: Top 5 rated products are GLoves, Sandals, Boots, Hat, and Skirt.

Recommendation: Implement customer loyalty programs, optimize discount policy, and targert marketing.

⚙️ How to Run
Python: Open notebooks/data_cleaning.ipynb and run all cells to generate the cleaned_data.csv.

SQL: Execute the scripts in /sql_queries/analysis.sql within your SQL editor.

Power BI: Open the .pbix file in the /dashboard folder (Note: You may need to update the data source path).

Presentation: View the project summary via the Gamma link provided in the /docs folder.
