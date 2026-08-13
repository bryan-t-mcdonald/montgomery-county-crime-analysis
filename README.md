#  Montgomery County, MD | Crime & Incident Analysis (2017–2025)

## Overview
Examined over **500,000 raw government incident records** from Montgomery County, MD spanning 2017 to 2025. Standardized the dirty raw dataset and added regional city population metrics to allow for more in-depth calculations. Designed an interactive Tableau dashboard to track high-frequency crime categories, trends over time, and geographical hot spots across the county.

---

## Project Resources
* ** Live Interactive Dashboard:** [View on Tableau Public]([https://public.tableau.com/app/profile/bryan.mcdonald/vizzes](https://public.tableau.com/views/MontgomeryCountyMDCrimeIncidentAnalysis2017-2025/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link))
* ** Cleaned & Raw Datasets:** [Download Compressed Datasets via GitHub Releases](https://github.com/bryan-t-mcdonald/montgomery-county-crime-analysis/releases/tag/v1.0.0)
* ** Original Data Source:** [Montgomery County Open Data Portal](https://data.montgomerycountymd.gov/Public-Safety/Crime/icn6-v9z3/about_data)

---

## How I Prepared the Data
Using **Microsoft Excel**, the raw dataset was cleaned and transformed before visual analysis:
* **Deduplication & Null Handling:** Removed administrative noise and handled missing geographical and timestamp attributes.
* **Handled Multi-Offense Entries:** Kept duplicate Incident IDs intact so that events involving multiple offenses (e.g., vandalism and theft happening in one call) were fully counted at the offense level.
* **Date Attribute Extraction:** Extracted custom time fields (`Year`, `Month`, `Day of Week`, `Peak Season`) to analyze trends over time.

---

## Key Takeaways
* **Peak Volume:** Total incident volume peaked during **October**, driven primarily by property-related offenses.
* **Top Category:** **Crimes Against Property** represented the majority of all recorded offenses across the 8-year timeframe.
* **Primary Hot Spot:** **Silver Spring** logged the highest overall incident count among police districts.
* **Most Frequent Offense:** **Theft From Motor Vehicle** consistently ranked as the #1 individual offense.

---

## Tools Used
* **Microsoft Excel:** Data cleaning, standardization, lookup functions, date extraction, feature engineering.
* **Tableau Desktop / Public:** Dynamic KPI card design, spatial density mapping (GIS), time-series line trends, cross-filtering dashboard layouts.
* **GitHub:** Version control and release-based dataset distribution.
