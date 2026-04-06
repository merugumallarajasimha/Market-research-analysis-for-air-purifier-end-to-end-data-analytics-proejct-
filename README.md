
🌬️ Market research  analysis for aur purifier
An End-to-End Data Science & Business Intelligence Roadmap for the Indian Air Purifier Market

📌 Project Overview
IT is a comprehensive data-driven strategy project designed to guide an air purifier startup through the complexities of the Indian environmental landscape. This project transitions from raw, fragmented atmospheric data to a high-fidelity 6-Page Executive Dashboard that identifies "Priority 1" launch zones, competitive feature gaps, and demographic vulnerabilities.

⚙️ The Data Engineering Pipeline (My Workflow)
The project follows a rigorous 4-stage analytical pipeline to ensure the "Single Version of Truth."

1. Extraction & Pre-processing (Python / Jupyter)
Raw datasets were often inconsistent, containing null values and non-standardized units. I used Python (Pandas, NumPy) in a Jupyter environment to perform:

Data Cleaning: Handled missing values and outliers in historical AQI logs (2022-2025).

Transformation: Renamed, trimmed, and standardized columns for schema consistency.

Feature Engineering: Worked on each individual column to create new attributes, such as "Risk Categories" based on global WHO standards.

Text Mining: Cleaned and normalized 100k+ consumer reviews to prepare for competitive sentiment analysis.

2. Data Modeling & Integration (Power BI / Power Query)
After the Python transformation, I imported the cleaned data into Power BI to build a robust Star Schema Architecture:

Fact Tables: Fact_AQI, Fact_Health_Impact.

Dimension Tables: Dim_City, Dim_Date, Dim_Pollutants, Dim_Competitors.

Multi-Select Logic: Used Power Query (M Language) to split "Multi-Select" survey responses (where users checked multiple health issues) into individual rows to ensure accurate counting and visualization.

3. Research & Secondary Analysis
To solve the complex secondary questions, I integrated external research and additional datasets:

Demographic Census: Overlaid population density and age-group data with pollution hotspots.

Competitor Benchmarking: Conducted online research on brands like Dyson, Philips, and Xiaomi to build a Competitive Feature-Gap Matrix.

📊 Key Dashboard Insights
The final 6-page report provides actionable answers to primary and secondary business questions:

Regional Hotspots: Identified the Top 5/Bottom 5 polluted areas and analyzed Weekday vs. Weekend fluctuations.

Health Correlation: Mapped AQI spikes to respiratory illnesses (Asthma, Bronchitis) across different age groups.

Consumer Awareness: Processed primary survey data to reveal the "Awareness-Action Gap" in the Indian public.

Winning Strategy: Concluded with a final roadmap recommending a ₹12,999 target price and a focus on Sensor Accuracy—the #1 gap in current rival products.

🛠️ Technical Stack & Skills
Languages: Python (Pandas, NumPy, BeautifulSoup), DAX (Data Analysis Expressions), Power Query (M).

Tools: Jupyter Notebook, Power BI Desktop, MySQL Workbench.

Specialized Visuals: Azure Maps API (Satellite & Heat Layer), Scatter Plots with Correlation Trend Lines.

Data Modeling: Star Schema, Many-to-One Relationships, Bridge Tables.


💡 Conclusion
This project demonstrates that in 2026, air quality isn't just an environmental metric—it's a critical business variable. By solving the primary consumer pain point identified through data, AirPure Innovations is positioned to successfully disrupt the Indian market.
