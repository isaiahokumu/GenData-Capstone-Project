# GenData-Capstone-Project

# Health Service Utilization & Disease Burden in Kenya

This project analyzes outpatient and inpatient health service data in Kenya, focusing on disease trends, facility performance and regional health disparities using SQL, Excel and Tableau.

---

## Objectives
My task in this project is to ensure I achieve the following;

- Identify the top diseases by frequency and demographic distribution.
- Analyze monthly trends in diseases like malaria, pneumonia, and diarrhoea.
- Measure service utilization at facilities (OPD/IPD ratios, admissions).
- Visualize health service data by region and facility using interactive dashboards.

---

## Tools Used

| Tool    | Purpose                          |
|---------|----------------------------------|
| SQL     | Data modeling, joining, and aggregation |
| Excel   | Cleaning, exploration, age group formatting |
| Tableau | Dashboard creation, geospatial mapping |

---

## Dataset Sources

- [Kenya Open Data Portal](https://www.opendata.go.ke)
- [WHO Global Health Observatory](https://www.who.int/data/gho)
- [UNICEF Statistics](https://data.unicef.org)
- [DHS Program](https://dhsprogram.com) (Kenya DHS, requires registration)

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

- Explore incorporating SHIF claims or immunization data
- Add population denominators for calculating disease rates
- Automate monthly updates using Tableau Prep or Python scripts

---

*Author: Isaiah Okumu*  
