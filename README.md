## Time-Series-Forecasting

### Name: Rohit Jain 
### Roll: 101903706
### Subject: Building Innovative Systems

# Multi-input time series data : Predicting values of 5 parameters.

- `allSectionsExcel`: this directory includes excel files generated for all the sections individually.
- `output` : this directory includes the predictions and expected output with RMSE between them.
- `visulaization` : this directory includes the plottings of predicted and expected value for all the sections.

- Each section file in `output` directory have 3 rows:
1st row : actual value
2nd row : predicted value
3rd row : Root Mean Square Error

### Input File (DATASET.xlsx)

- Original dataset contains 1009 rows and 15 columns.
- Dataset is divided into 101 sections.
- First column denotes each road section.
- Second column denotes the year no. for which parameter values are recorded.
- Columns 3 to 15 represents values for parameters 1 to 13.

### Requirements

- Predict values for coulumn 9 to 13 for last (10th) year of each road section.
- Visualizing the predicted and actual values, plotting graphs.

### Methodology

- Gradient Boosting: decision trees for Regression
- Light Gradient Boosting Machine - Regression Model
- Boosting

### Evaluation Metric

- RMSE: Root Mean Square Error

### Result

Final RMSE = 34.091
