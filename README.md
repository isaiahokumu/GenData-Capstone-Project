# GenData-Capstone-Project

# Malaria Epidemiology Framework for Data Analytics

This project aims to analyze malaria incidence cases, transmission patterns and donor distribution across different regions to inform public health policy and resource allocation decisions using SQL, Excel and Tableau.

---
## Problem Statement
Despite global efforts advanced by the United Nations (UN) through the World Health Organization (WHO) to reduce malaria’s global burden, malaria remains the second leading cause of mortality in Sub-Saharan Africa. Countries that have adopted the National Malaria Program framework are making significant milestones across the region. This progress seems to face hindrances through fragmented data on malaria incidence, mortality rates, and intervention effectiveness. This fragmentation impedes policymakers' ability to design timely and targeted responses. Recent cuts in donor funding, particularly from the United States Agency for International Development (USAID) under the Trump administration, further threaten malaria control efforts. This project aims to analyze trends in malaria mortality rates, assess the patterns and effects of donor funding over time, and evaluate how these factors influence the malaria burden in Sub-Saharan Africa to generate actionable insights for policy and intervention planning.

---

## Objectives
Overview
This project aims to analyze trends in malaria incidence cases, transmission patterns, and donor distribution across different regions to inform public health policy and resource allocation decisions.

---

## Tools Used

| Tool    | Purpose                          |
|---------|----------------------------------|
| SQL     | Data modeling, joining, and aggregation |
| Excel   | Cleaning, exploration |
| Tableau | Dashboard creation, geospatial mapping |

---

## Dataset Sources

- [[WHO Global Health Observatory](https://www.who.int/data/gho)](https://www.who.int/publications/m/item/annexes-world-malaria-report-2024)
- [UNICEF Statistics](https://data.unicef.org)

---

## Data Pipeline

1. **Raw Data Collection**: CSV/Excel files of patient visits, diagnosis data, and facility metadata.
2. **Cleaning**: Handling in Excel – removing blanks, standardizing column names, grouping age.
3. **SQL Integration**: Loading cleaned data into SQL tables; Joining and queriying for KPIs.
4. **Visualization**: Build Tableau dashboards with filters, KPIs, maps, and trends.

---

## Key Dashboards

- **Overview Dashboard**: Total visits, top diseases, reporting facilities
- **Disease Trends**: Monthly trends, demographic slices (age/gender)
- **Facility Utilization**: OPD vs IPD pie charts, heatmaps of facility activity
- **Interactive Map**: County-level views of disease burden and service availability

---

## Project Structure

- `/data/` - All raw and cleaned datasets.
- `/sql/` - SQL scripts for schema setup, transformations, queries.
- `/tableau/` - Tableau dashboard file and visual assets.
- `/reports/` - PDF/doc summary of key insights and recommendations.

---

## Stretch Goals

- Predictive Modeling for Malaria Outbreaks
- Automate monthly updates using Tableau Prep or Python scripts
- Open Data Repository

---

*Author: Isaiah Okumu*  
