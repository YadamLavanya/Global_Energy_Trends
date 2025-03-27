🌍 Global Energy Trends: A Comprehensive Analysis with Power BI
📌 Project Overview
The Global Energy Trends project is a Power BI Data Analytics Dashboard designed to analyze worldwide energy consumption patterns, compare renewable vs. non-renewable sources, and provide insights into energy sustainability.

This project includes data cleaning, transformation, and visualization to help users understand energy trends across continents and key power-generating nations.

🚀 Step-by-Step Execution
1️⃣ Data Collection & Import
📌 Datasets Used:
We used six datasets in this project:

Continent – Mapping energy data to continents.

Country – Country-level energy data.

Renewable – Renewable energy consumption and trends.

Non-Renewable – Data on fossil fuel-based energy consumption.

Renewable Power Generation – Contribution of renewables to power generation.

Top 20 Countries Power Generation – Highest energy-producing nations.

🔹 Steps to Load Data into Power BI:

Open Power BI Desktop

Click on "Home" → "Get Data"

Select Excel, CSV, or SQL Server as per the dataset format

Browse and select the six datasets

Click Load to import them into Power BI

2️⃣ Data Cleaning & Transformation
After loading the data, we used Power Query Editor for data preprocessing.

🔹 Key Data Cleaning Steps:
✔️ Removed null/duplicate values
✔️ Standardized date and time formats
✔️ Merged datasets using common fields (e.g., Country, Year)
✔️ Renamed columns for clarity
✔️ Created calculated columns for total energy share, % renewables, and CO₂ emissions

📌 Steps in Power BI:

Go to Power Query Editor

Apply data cleaning transformations

Create custom measures using DAX

Click Close & Apply to save changes

3️⃣ Data Modeling
To establish relationships between datasets, we used Power BI’s Model View.

🔹 Steps to Create Data Relationships:

Navigate to Model View

Drag & connect datasets based on common fields

Set One-to-Many relationships (e.g., Country Table → Renewable Data)

Verify relationship direction to maintain accuracy

4️⃣ Dashboard Creation & Visualizations
After data preparation, we built interactive dashboards for analysis.

🔹 Key Power BI Visuals Used:
📊 Line Charts: Energy consumption trends over time
📊 Bar Charts: Renewable vs. non-renewable comparisons
📊 Pie Charts: Power generation distribution by source
📊 Maps: Geographic analysis of energy usage

📌 Steps to Create Dashboards:

Open the Report View

Select Visualization Pane → Drag required visuals

Choose appropriate fields & filters

Format and apply conditional formatting for better insights

Publish report to Power BI Service (if needed)

5️⃣ Insights & Analysis
Key insights derived from the dashboard:
✔️ Renewable energy adoption is increasing in developed nations
✔️ Top energy-consuming countries include USA, China, India
✔️ CO₂ emissions are higher in regions dependent on non-renewables
✔️ Solar & wind power growth is accelerating in Europe & Asia

6️⃣ Final Report & Presentation
We compiled findings into a Power BI Report and PDF documentation, including:
📌 Data cleaning & transformation steps
📌 Dashboard walkthrough
📌 Insights & recommendations

📢 Contributors
👤 Lavanya
👤 Anjali
👤 Neha Vaishnavi
👤 Ram Kumar
