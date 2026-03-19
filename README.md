Minnesota Traffic Analysis (BI Project)
📊 View Interactive Tableau Dashboard
📌 Project Overview
An end-to-end Business Intelligence project developed for the Minnesota Department of Transportation. This project transforms raw interstate traffic data into a multi-layered dashboard to identify congestion patterns and environmental impacts.

📋 Stakeholder Requirements
Temporal Trends: Analyze traffic by Year, Month, Day, and Hour.

Weather Impact: Correlate traffic volume with 11+ different weather conditions.

Holiday Analysis: Identify specific holidays with the highest traffic density.

Real-time Simulation: Manage incomplete 2018 data to reflect live reporting scenarios.

🛠️ Technical Implementation
Data Sources: Cleaned and joined raw CSV traffic datasets.

Custom Metrics: Engineered a custom holiday dimension to isolate peak travel dates:

IF [Holiday] = "None" THEN NULL ELSE "X" END

Advanced Visuals: * Heatmaps: Hour-of-day vs. Day-of-week congestion matrix.

Bubble Charts: Multi-variable analysis using Size & Color for holiday volume.

Dual-Axis Charts: YoY monthly traffic comparisons (2016-2018).

📈 Key Insights & Results
Weather Factors: Traffic volume peaks at 24M+ during clear weather but drops by over 50% during significant rain/snow events.

Peak Hours: Identified critical "Hot Zones" in traffic concentration using density mapping.

Seasonal Shifts: Comparison of 2016-2018 data revealed consistent month-over-month growth trends until Q3 2018.

📂 Project Deliverables
Tableau Workbook: Interactive Story and Dashboard.

Stakeholder Presentation: PPT deck translating technical charts into business-ready recommendations.

Documentation: Full README and technical troubleshooting log.
