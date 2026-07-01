# Coffee-Sales-Dashboard
This project is an end-to-end Power BI Business Intelligence Dashboard developed to analyze and visualize the sales performance of a coffee shop chain. The dashboard transforms raw transactional data into meaningful business insights through data modeling, DAX calculations, and interactive visualizations.

# Project Development Process

This dashboard was developed by following a structured data analytics workflow, starting from raw data preparation and ending with an interactive business intelligence solution. The first step involved understanding the business requirements and identifying the key metrics needed to evaluate the performance of the coffee shop business. The dataset was then explored to understand its structure, relationships, and the information available for analysis.

The data was imported into **Power BI** and transformed using **Power Query**. During this stage, data types were corrected, unnecessary columns were removed, missing values were reviewed, and the data was prepared for analysis. A dedicated **Calendar Table** was created using DAX to support time-based calculations and enable accurate month-over-month analysis.

After cleaning the data, a **Star Schema** was designed by connecting the **FactSales** table with the **Customer**, **Product**, **Store**, **Promotion**, and **Calendar** dimension tables. This approach improved the performance of the data model while making calculations easier to manage and maintain.

The next stage focused on creating reusable **DAX measures** for important business metrics such as Total Revenue, Total Profit, Total Transactions, Average Order Value, Profit Margin, Previous Month values, and Month-over-Month growth percentages. To keep the model organized, the measures were grouped into folders based on their functionality, making future updates more efficient.

Once the data model was complete, the dashboard layout was designed with a focus on clarity and user experience. Interactive slicers were added to allow users to filter the report by **Segment**, **Year**, and **Region**. Various visualizations were used to present monthly revenue trends, store performance, product category analysis, and revenue distribution across different store types. Dynamic insight measures were also created to display meaningful business observations directly within the dashboard.

Finally, the dashboard was reviewed to ensure that calculations were accurate, filters worked correctly, and the visuals provided a clear representation of business performance. The completed report delivers an interactive and user-friendly solution that enables stakeholders to monitor sales performance, identify trends, compare store performance, and make informed business decisions based on data.

# Workflow

* Understood the business requirements and explored the dataset.
* Cleaned and transformed the data using **Power Query**.
* Built a **Star Schema** by creating relationships between fact and dimension tables.
* Created a **Calendar Table** and developed DAX measures for KPIs and time intelligence.
* Designed an interactive dashboard with slicers, KPI cards, charts, and dynamic business insights.
* Validated the report to ensure accurate calculations, consistent filtering, and meaningful visual storytelling.
