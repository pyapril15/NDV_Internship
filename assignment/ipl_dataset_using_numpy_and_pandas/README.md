
# IPL Dataset Cleaning and Preprocessing

## Objective
This project aims to clean and preprocess the IPL (Indian Premier League) datasets using **Pandas** and **NumPy**. It involves handling missing data, removing duplicates, performing transformations, and visualizing key insights.

## Files
- `matches.csv` - Original IPL match-level dataset.
- `deliveries.csv` - Original IPL ball-by-ball dataset.
- `cleaned_matches.csv` - Cleaned version of the matches dataset.
- `cleaned_deliveries.csv` - Cleaned version of the deliveries dataset.
- `ipl_dataset_stats.py` - Python script or notebook with all cleaning steps.

## Tasks Performed

### Data Cleaning
- Loaded datasets using Pandas
- Inspected missing values using `.info()` and heatmaps
- Handled missing values via:
  - Filling with appropriate placeholders (`fillna`)
  - Dropping columns with excessive nulls
- Removed duplicate rows

### Data Transformation
- Converted date fields to datetime format
- Normalized numerical fields (e.g., `result_margin`) using NumPy
- Label encoded categorical fields for ML-readiness

### Analysis & Visualization
- Heatmaps of missing data
- Correlation matrix of numerical fields
- Top players of the match
- Total runs scored by teams

## Bonus Points Covered
-  Visualized null value distributions
- Generated correlation matrix of numerical fields
-  Applied label encoding for ML readiness

## Requirements
- Python 3.x
- pandas, numpy, matplotlib, seaborn, scikit-learn

## How to Run
1. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn`
2. Run the script: `python ipl_dataset_stats.py` or open in Jupyter Notebook.
3. Check output files: `cleaned_matches.csv` and `cleaned_deliveries.csv`.

## Author
- Praveen Yadav

## Date
- 27/05/2025
