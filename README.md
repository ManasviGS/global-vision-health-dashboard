# Global Vision Health Dashboard

An interactive Power BI dashboard analyzing global vision impairment and blindness trends from 1990–2023.

<table><tr>
<td><img src="https://github.com/user-attachments/assets/7194d1da-549a-4d14-9cb4-80ccecaa6c4d" width="480"/></td>
<td><img src="https://github.com/user-attachments/assets/42e2932a-67fc-4ede-83ce-070c32803d81" width="480"/></td>
</tr></table>

Overview
Built to analyze key KPIs related to vision health across 7 conditions over 33 years, using real-world epidemiological data from IHME.

Key Insights
- Refraction disorders affect the most people globally (~4bn cumulative cases)
- Cataract is the #2 cause, and the fastest growing surgical target
- All major conditions show consistent upward trends from 1990–2023
- Total global prevalence of vision conditions exceeded 1.65bn in 2023

Dashboard Features
- KPI cards: Total cases, Average prevalence, 2023 snapshot
- Bar chart: Prevalence by cause (filterable)
- Line chart: Trend over time by condition (1990–2023)
- Interactive year slicer: filter all visuals dynamically

Tools & Techniques
- **Tool:** Microsoft Power BI Desktop
- **DAX measures:** SUM, AVERAGE, CALCULATE with year filter
- **Data modelling:** Star schema with Date table
- **ETL:** Power Query for data type casting and column cleanup

Data Source
IHME Global Burden of Disease 2023
[vizhub.healthdata.org/gbd-results](https://vizhub.healthdata.org/gbd-results/)
Conditions: Cataract, Glaucoma, Refraction disorders, Age-related macular degeneration, Other vision loss

Relevance
Built as part of preparation for a data analytics internship focused on Vision care operations — directly aligned with real-world ophthalmic KPI reporting.
