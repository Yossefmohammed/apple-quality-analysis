# Apple Quality Analysis

## Project Overview
This project analyzes a dataset of apple quality measurements to understand the factors that contribute to apple quality. The analysis includes data exploration, visualization, and statistical analysis to identify patterns and relationships between various apple characteristics and their overall quality.

## Dataset
The dataset contains 4000 entries with the following features:
- A_id: Apple identifier
- Size: Apple size measurement
- Weight: Apple weight measurement
- Sweetness: Apple sweetness level
- Crunchiness: Apple crunchiness measurement
- Juiciness: Apple juiciness level
- Ripeness: Apple ripeness measurement
- Acidity: Apple acidity level
- Quality: Target variable (good/bad)

## Analysis Steps
1. Data Loading and Initial Exploration
   - Loaded the dataset using pandas
   - Examined basic statistics and data structure
   - Checked for null values and duplicates

2. Data Cleaning
   - Removed null values
   - Dropped unnecessary columns (A_id)
   - Verified data integrity

3. Exploratory Data Analysis
   - Analyzed the distribution of quality classes (good/bad)
   - Created visualizations to understand feature distributions
   - Generated box plots to identify outliers in key features:
     - Size
     - Weight
     - Sweetness
     - Crunchiness

4. Key Findings
   - The dataset contains 2004 good quality and 1996 bad quality apples
   - Multiple features show significant outliers that may need further investigation
   - Visual analysis revealed patterns in the relationship between physical characteristics and quality

## How to Run the Project
1. Ensure you have the following Python packages installed:
   - pandas
   - matplotlib
   - numpy

2. Clone this repository

3. Open the `apple-quality-analysis.ipynb` notebook in Jupyter

4. Run the cells sequentially to reproduce the analysis

## Requirements
- Python 3.10.13
- Jupyter Notebook
- Required Python packages as listed in the notebook

## Data Source
The dataset was obtained from Kaggle and contains measurements of various apple characteristics.

## License
This project is open source and available for educational and research purposes.