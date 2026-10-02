# Parental-Reporting-of-Activities-Relevant-for-Young-Children-s-Soil-Dust-Ingestion
Parental Reporting of Activities Relevant for Young Children’s Soil/Dust Ingestion 
<img width="1866" height="800" alt="image" src="https://github.com/user-attachments/assets/74fe2991-dea0-4bb9-8e5e-d354d0e114cb" />
## Child Soil/Dust Ingestion Behavior Survey Analysis

This repository contains summary tables, reports, and interactive visualizations associated with the manuscript:

*Ferguson, A., Hasan, A., Adelabu, F., Fayad-Martinez, C., Ogunseye, O., Gidley, M., Honan, J., Beamer, P. I., & Solo-Gabriele, H.*  
*Parental reporting of activities relevant for young children’s soil/dust ingestion.*  
**Scientific Reports**, 16, 12500 (2026).  
https://doi.org/10.1038/s41598-026-40220-3

## Project Summary

This project analyzes parent-reported activities related to young children’s ingestion of soil and dust. The study focuses on children aged 6 months to 6 years and examines behaviors such as mouthing, pacifier use, blanket use, sucking fingers or toes, handwashing, outdoor play, daycare play, park play, and sandbox access.

The analysis compares child behavior variables with demographic and household variables, including child age group, child race, parent race, household income, parent education, parent work status, and city. Associations were evaluated using chi-square tests of independence and Cramér’s V.

## Repository Contents

### Main Reports

| File | Description |
|---|---|
| `Complete Survey Analysis Report.html` | Complete HTML analysis report. |
| `Complete Univariate and Bivariate Analysis Report.pdf` | Static PDF report summarizing univariate and bivariate results. |

### Interactive Visualizations

| File | Description |
|---|---|
| `sankeyNetwork.html` | Interactive Sankey network visualization. |
| `sankey_plot.html` | Additional Sankey-style visualization. |

### CSV Summary Tables

The CSV files provide paired frequency and relative frequency summaries for selected behavior-demographic combinations.

| Topic | Variables Summarized |
|---|---|
| Child behaviors by age group | Blanket, mouthing, pacifier, pacifier use, pacifier washing, sucking |
| Daycare play | Household income, parent degree, parent work status |
| Park play | Child race, parent race |
| Other play locations | City |
| Sandbox access at home | City |

Each topic generally includes both a `Frequency.csv` file and a corresponding `Relative Frequency.csv` file.

## File List

```text
Complete Survey Analysis Report.html
Complete Univariate and Bivariate Analysis Report.pdf
sankeyNetwork.html
sankey_plot.html

Blanket Child_Age_Gp Frequency.csv
Blanket Child_Age_Gp Relative Frequency.csv
Mouthing Child_Age_Gp Frequency.csv
Mouthing Child_Age_Gp Relative Frequency.csv
Pacifier Child_Age_Gp Frequency.csv
Pacifier Child_Age_Gp Relative Frequency.csv
Pacifier_Use Child_Age_Gp Frequency.csv
Pacifier_Use Child_Age_Gp Relative Frequency.csv
Pacifier_Wash Child_Age_Gp Frequency.csv
Pacifier_Wash Child_Age_Gp Relative Frequency.csv
Sucking Child_Age_Gp Frequency.csv
Sucking Child_Age_Gp Relative Frequency.csv

Play_Daycare Household_income Frequency.csv
Play_Daycare Household_income Relative Frequency.csv
Play_Daycare P1_Degree Frequency.csv
Play_Daycare P1_Degree Relative Frequency.csv
Play_Daycare P1_Workstatus Frequency.csv
Play_Daycare P1_Workstatus Relative Frequency.csv
Play_Other City Frequency.csv
Play_Other City Relative Frequency.csv
Play_Park Child_Race4 Frequency.csv
Play_Park Child_Race4 Relative Frequency.csv
Play_Park P1_Race4 Frequency.csv
Play_Park P1_Race4 Relative Frequency.csv
Sandbox_Home City Frequency.csv
Sandbox_Home City Relative Frequency.csv
