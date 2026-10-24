# Matching Parents and Children with SQL in Python: Estimating IGE and Life-Cycle Bias
This project creates simulated longitudinal household panel data, uses SQL joins to match parents and children, and compares intergenerational income elasticity (IGE) estimates from single-year income and multi-year average income. It demonstrates life-cycle bias caused by transitory income shocks.

## Repository Structure
- analysis.Rmd: Full analysis, code and written discussion for submission
- analysis.html: Rendered webpage
- /data: Simulated panel datasets in CSV format
- /figures: Exported scatter plots (PNG)

## Replication Instructions
1. Open analysis.Rmd in RStudio
2. Install required packages: tidyverse, dbplyr
3. Knit the document. All datasets and figures will be saved automatically into the /data and /figures folders.
4. The two scatter plots compare IGE estimates before and after averaging income to reduce temporary income noise.

## Notes
The data is randomly simulated. Parental permanent income and child permanent income are independently generated, so the resulting IGE coefficients are negative. The exercise focuses on illustrating life-cycle bias as a statistical mechanism.
