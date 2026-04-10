# Global Layoff Trends & Sector Analysis (2020–2023)

## Project Overview
This project provides a metrics-driven exploration of global tech-sector instability, spanning from the onset of the COVID-19 pandemic to the early adoption phase of generative AI. By analyzing **383,000+ layoffs** across **1,995 companies** in **51 countries**, the study identifies the macroeconomic drivers and strategic shifts that transformed the labor market from a "survival" mindset to a "year of efficiency."

## Data & Methodology
The analysis was built on an end-to-end data pipeline designed to handle significant real-world data quality challenges.

* **Tech Stack:** * **Python (Pandas):** Automated data cleaning and null handling.
    * **SQL:** Complex data transformations and multi-dimensional aggregations.
    * **Tableau 2024.2:** Interactive dashboarding and geospatial visualization.
* **Process:**
    * Ingested 2,361 raw records.
    * Resolved critical data gaps: 740 nulls in `total_laid_off` and 785 nulls in `percentage_laid_off`.
    * Standardized inconsistent date formats to `YYYY-MM-DD`.
    * Normalized categorical fields (industry, country) and removed 366 invalid or duplicate entries.

## Key Insights
* **The 2021 Paradox:** Recorded as the "quietest" year (15,823 layoffs), but near-zero interest rates led to aggressive hiring that deferred economic pain into 2022.
* **The 2022 Surge:** A **649% increase** in layoffs triggered by rising interest rates and inflation. Post-IPO companies were the primary drivers, accounting for 204,132 layoffs.
* **The 2023 "Year of Efficiency":** Q1 2023 alone surpassed the entirety of 2022 with **167,000+ layoffs**. This phase represented a "strategic correction," with average workforce reductions dropping to 20% (vs. 30% in 2020).
* **AI Disruption:** Observed a **38.7% spike** in layoffs correlating with generative AI adoption, signaling a major labor shift toward modern AI infrastructure.

## Impact Analysis
* **Sector Volatility:** The **Consumer** and **Retail** sectors were the hardest hit, representing ~23% of total global layoff volume.
* **Geographic Concentration:** The **United States** dominated the dataset (67% of layoffs), followed by **India** (~9%).

## Visualizations
The final Tableau dashboard includes:
1.  **Macroeconomic Trends:** Historical line graphs overlaying layoff spikes with Fed rate hikes.
2.  **Industry vs. Funding:** Bar charts comparing layoff volume against funds raised, segmented by company stage.
3.  **Global Heatmap:** Geospatial analysis identifying layoff intensity by country and region.
4.  **Company Granularity:** Drill-down views tracking percentage-based workforce reductions for specific organizations.
