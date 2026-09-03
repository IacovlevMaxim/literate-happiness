# Dengue Diagnosis and Classification

## Files Overview

- `00_model.ipynb` - preliminary model testin to determine baseline performance and feature importance
- `01_EDA.ipynb` - exploratory data analysis to identify statistical trends, biases, numerical distributions, correlations etc.
- `02_Missing_Values.ipynb` - identify the best method for imputing missing data entries
- `03_Feature_Engineering.ipynb` - propose engineered features based on statistical evidence and determine their importance
- `04_Outlier_Method.ipynb` - analyse multiple outlier filtering methods and choose the best one for given dataset
- `05_Feature_Select.ipynb` - use RFECV to identify optimal features for classification
- `06_Class_Balancing.ipynb` - try out several class balancing methods to balance outcome column
- `07_PCA.ipynb` - use Principal Component Analysis to identify explained variance for each number of principal components
- `08_Model_Selection.ipynb` - identify which model work best for PCA and Engineered datasets and perform model interpretation
- `09_Final.ipynb` - assemble the entire workflow into a single pipeline and evaluate it on the test dataset