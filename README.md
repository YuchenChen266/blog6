# Matching Parents and Children with SQL in Python: Estimating IGE and Life-Cycle Bias
This project creates simulated longitudinal household panel data, uses SQL joins to match parents and children, and compares intergenerational income elasticity (IGE) estimates from single-year income and multi-year average income. It demonstrates life-cycle bias caused by transitory income shocks.

## Repository Structure
- blog6.ipynb: Full analysis, code and written discussion for submission
- blog6.html: Rendered webpage
- /figures: Exported scatter plots (PNG)

## Replication Instructions
1. Open blog6.ipynb
2. Install required packages: pandas, sqlite3, matplotlib, numpy
3. Run all cells. The code generates simulated data automatically and saves figures into the /figures folder.
4. The two scatter plots compare IGE estimates before and after averaging income to reduce temporary income noise.

## Notes
The data is randomly simulated inside the notebook. Parental permanent income and child permanent income are generated within the code, so no external CSV data file is needed. The exercise focuses on illustrating life-cycle bias as a statistical mechanism.
