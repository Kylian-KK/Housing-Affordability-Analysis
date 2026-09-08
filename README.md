# Housing Affordability Analysis in Canada

Objective

This project analyzes housing affordability in Canada by comparing household housing costs and incomes in Ontario and British Columbia. The analysis aims to identify the households that face the greatest financial pressure and to examine how affordability varies according to province, household type and number of bedrooms.

The central indicator is the ratio between housing costs and household income. This ratio is used to classify households into affordability categories and to support comparisons between different population groups.

Data Used

The project uses Canadian census data containing socio-economic and housing-related variables. The dataset includes information about household income, housing costs, province, household type and number of bedrooms.

Data dimension
Description
Geography
Ontario and British Columbia
Economic variables
Household income and housing costs
Household variables
Household type and number of bedrooms
Main derived indicator
Housing-cost-to-income ratio
Main analytical purpose
Compare housing affordability between population groups




The exact definitions of the variables and the source dataset should be documented in the accompanying notebook before publication.

Methodology

The analysis follows a structured exploratory workflow.

First, the dataset is imported and inspected to understand its dimensions, variable types and possible data-quality issues. Missing values, invalid entries and inconsistent formats are identified before the analysis begins.

Second, a housing-cost-to-income ratio is calculated for each observation. This indicator provides a common basis for comparing households with different income levels.

Third, observations are grouped into affordability categories such as affordable housing, high housing cost burden and severe housing-cost pressure. The thresholds used for these categories should be stated explicitly and justified in the notebook.

Fourth, the results are compared by province, household type and number of bedrooms. Boxplots, bar charts and stacked bar charts are used to examine differences in distributions and proportions.

Finally, correlations between housing, income and household characteristics are explored. Correlation results are interpreted as associations and should not be presented as proof of causation.

Results

The project is designed to answer the following questions:

1.  How does housing affordability differ between Ontario and British Columbia?

2.  Which household types experience the highest housing-cost burden?

3.  Does the number of bedrooms appear to be associated with housing costs or affordability?

4.  How are households distributed across the affordability categories?

5.  Which socio-economic variables are most strongly associated with housing affordability?

The main outputs are comparative visualizations showing the distribution of housing-cost-to-income ratios and the proportion of households in each affordability category. The notebook should include the exact numerical findings that support the final interpretation.

Technologies

Technology
Use in the project
Python
Main programming language
Pandas
Data loading, cleaning and transformation
Matplotlib
Data visualization
Seaborn
Statistical charts and distribution plots
Jupyter Notebook
Analysis, documentation and presentation of results




Limitations and Possible Improvements

The interpretation depends on the quality and scope of the census data. A ratio based only on housing costs and income may not capture transportation expenses, debt, household savings, regional price differences or other financial obligations.

The affordability categories also depend on the selected thresholds. These thresholds should be documented and tested through a sensitivity analysis to determine whether the conclusions remain stable when the limits change.

Future improvements could include adding more provinces, analyzing changes over time, distinguishing between renters and homeowners, incorporating household size and studying the relationship between housing affordability and demographic characteristics.

Project Structure

Plain Text


housing-affordability/
├── data/

│   └── housing_data.csv

├── notebooks/

│   └── housing_affordability_analysis.ipynb

├── images/

│   └── housing-affordability.jpg

└── README.md



How to Run the Project

1.  Clone or download the project repository.

2.  Install the required Python libraries.

3.  Place the dataset in the expected data/ directory.

4.  Open the notebook in Jupyter Notebook or JupyterLab.

5.  Run the cells in order from data loading to interpretation.

A typical installation command is:

Bash


pip install pandas matplotlib seaborn jupyter



Accessibility Description


References

[1] Pandas documentation

[2] Matplotlib documentation

[3] Seaborn documentation

[4] Jupyter documentation

[5] Statistics Canada Census Program



Author

Kylian Kouda Kuete

This project was developed as part of an academic portfolio in data analysis and applied data science.

