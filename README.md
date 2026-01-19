# thesis-github-link
Repository containing raw FTSE 350 ESG and financial datasets, Python scripts for cleaning, merging and feature creation, and fully executed analysis code reproducing all dissertation results. Includes README with data sources and links.

README

FTSE 350 ESG and Financial Performance Dissertation Repository

Purpose
This repository provides the complete materials used to produce the empirical results reported in the dissertation examining the relationship between ESG performance and corporate financial performance for FTSE 350 firms, including cross-sector comparison, firm-size moderation, governance mediation testing, and machine learning-based technical validation.

Repository contents
This repository contains:

1. The raw FTSE 350 ESG and financial dataset export used in the dissertation 
2. Python scripts for data cleaning, merging, and variable construction
3. Executed analysis code that reproduces all reported statistical outputs and tables
4. A data dictionary describing dataset fields, transformations, and modelling roles

Data source
All variables were exported from LSEG Refinitiv using LSEG Workspace. The export includes Refinitiv ESG scores and components, governance variables, and financial and market indicators used in the empirical models.

General product links (LSEG Refinitiv)
LSEG Workspace:
[https://www.lseg.com/en/data-analytics/products/workspace](https://www.lseg.com/en/data-analytics/products/workspace)

LSEG ESG Scores:
[https://www.lseg.com/en/data-analytics/sustainable-finance/esg-scores](https://www.lseg.com/en/data-analytics/sustainable-finance/esg-scores)

LSEG ESG Data:
[https://www.lseg.com/en/data-analytics/financial-data/company-data/esg-data](https://www.lseg.com/en/data-analytics/financial-data/company-data/esg-data)

Licensing note
Refinitiv data is typically distributed under institutional licence. If the raw export cannot be shared publicly, the repository still provides the full analysis pipeline and documentation. Users with authorised access can re-export the same data fields from LSEG Workspace and reproduce the results by running the scripts.

Reproducing the dissertation results
Install Python and the relevant. Place the Refinitiv export file in the repository using the filename referenced in the cleaning script. Run the scripts in this sequence: cleaning and merging, feature engineering, econometric modelling, machine learning validation. The workflow recreates the full set of dissertation outputs, including regression tables, sector-stratified coefficients, moderation and mediation results, and validation metrics.

Repository link
https://github.com/Ewuraba/thesis-github-link 

Author
Ewuraba Dede Dick, MSc Business Analytics, [University of Greenwich]
