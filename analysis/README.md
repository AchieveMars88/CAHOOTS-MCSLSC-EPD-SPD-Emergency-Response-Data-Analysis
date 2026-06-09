# Analysis Overlook

The following folder utilizes the "analysis.ipynb" notebook to appropriately derive necessary statistics and visuals. This analysis compares response times, call densities, call classifications, and call closure outcomes across different weather conditions.

The notebook performs:
- CAHOOTS call extraction
- Weather-based filtering
- Response time analysis
- Call density analysis
- ANOVA significance testing
- Tukey HSD post-hoc testing
- Visualizations & Regression

## Associated Data:

1. Eugene Police Department (EPD/CAD & CAHOOTS - CAD_CLEAN)
2. Springfield Police Department (SPD & CAHOOTS - SPD_CLEAN)
3. Mobile Crisis Services of Lane County (MCSLC - MCSLC_CLEAN)

## Python Version

Recommended: Python 3.11+
The notebook has been tested using Anaconda but should work in any standard Python environment.

## Dependencies:

pip install pandas matplotlib seaborn scipy statsmodels jupyter

or

conda install pandas matplotlib seaborn scipy statsmodels jupyter

pandas - Data manipulation
matplotlib - Plotting
seaborn - Statistical visualization
scipy.stats - Statistical analysis
statsmodels - ANOVA and Tukey HSD testing
Jupyter	Notebook - execution

## Running the Notebook:

If compressed datasets are used, update the notebook file paths accordingly:

pd.read_csv("../cleaning/Eugene_CAD_Data/CAD_CLEAN.csv.gz")
pd.read_csv("../cleaning/Springfield_SPD_Data/SPD_CLEAN.csv.gz")
pd.read_csv("../cleaning/MCSLC_Data/MCSLC_CLEAN.csv.gz")

1. Save the data as formatted in the repository to a local directory (exclude the raw data files).
2. Run the notebook. All associated code should run accordingly, as two others have tested with success.


