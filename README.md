# Apple-iTunes-Music-Store---Analytics-Business-Intelligence-Report


🎵 Apple iTunes Music Store: Business Intelligence & SQL Analytics
📌 Project Overview
Apple iTunes manages a massive digital music store network featuring millions of tracks and thousands of global customers. As the store scales, leadership requires deeper visibility into consumer behavior, content performance, and regional sales efficiency to drive growth.
+3

This project involved building a complete SQL-based analytical pipeline to transform raw CSV data into actionable business recommendations. By constructing a robust, fully relational database, I mapped millions of data points to identify high-value "whale" customers, top-performing genres, and geographic growth opportunities.
+3

🛠️ Tech Stack & Methodology
Data Ingestion & ETL: Used Python to merge and clean separate data files into a unified structure for efficient SQL import.


Database Management: Designed and deployed a relational schema in PostgreSQL/MySQL consisting of 11 distinct tables.
+3


Advanced Analytics: Leveraged JOINS, Window Functions (RANK, PARTITION BY), CTEs, and Subqueries to segment users and rank products.
+1


Visualization: (Optional) Integrated analytical outputs into Power BI/Tableau dashboards to track KPIs like monthly revenue and top artists.
+1

📊 Relational Database Schema
The database architecture connects 11 normalized tables to ensure data integrity:
+1

Content: track, album, artist, genre, media_type

Sales: invoice, invoice_line

Users: customer, employee

Engagement: playlist, playlist_track

💡 Key Business Insights
1. Geographic & Operational Leadership

Top Market: The USA is the primary revenue driver with 131 invoices and over $1,040 in total revenue.
+2


Event Strategy: Prague was identified as the most profitable city ($273.24 revenue), making it the ideal location for a promotional Music Festival.
+2


Seniority: Andrew Adams (General Manager, Level L6) is the senior-most employee managing the global network.
+1

2. Customer Behavior

"Whale" Identification: František Wichterlová is the highest-spending customer globally with a lifetime value of $144.54.
+2


Staff Performance: Jane Peacock is the top-performing sales representative, contributing $1,731.51 in attributed revenue.
+3

3. Product & Content Performance

Genre Dominance: Rock is the foundational pillar of the store, both in track count (99 tracks) and purchase volume.
+3


Top Talent: AC/DC is the most purchased artist with 124 purchases, and their track "Put The Finger On You" is the store's top-selling song.
+3

🚀 Strategic Recommendations

Hyper-Localized Marketing: Weight marketing spend toward North America (USA and Canada) while utilizing localized genre data to promote "Rock" in high-demand regions.
+1


Target the "Whales": Implement a VIP loyalty program for the top-ranked customers globally and locally to maximize lifetime value.
+1


Optimize the Catalog: Prioritize licensing for classic Rock catalogs and implement bundling strategies to increase the average invoice value above the $7.67 baseline.
+2


Operational Benchmarking: Use the client-retention strategies of top employees like Jane Peacock and Margaret Park as training standards for the broader sales team.
+1

📂 Project Structure
Plaintext
├── data/               # Raw CSV files
├── sql_queries/        # All 15 core analytical SQL scripts
├── dashboard/          # Power BI / Tableau project files
├── report/             # Final Business Intelligence PDF
└── README.md
👤 Author
Laveena Majeed

Data Analyst | Business Intelligence Specialist 
+1

LinkedIn Profile
