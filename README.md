# Insurance Data Analysis with Linear Regression
*This Jupyter Notebook code analyzes insurance data and demonstrates how age affects insurance costs using linear regression.*

## Table of Contents
- Description
- Dependencies
- Usage
- Results

### Description
*This code uses the insurance data from the "insurance.csv" file to perform the following tasks:*
- Load the insurance data into a Pandas DataFrame.
- Visualize the relationship between age and insurance charges using a scatter plot.
- Fit a linear regression model to predict insurance charges based on age.
- Make predictions on insurance charges for a given age.
- Display the scatter plot and the linear regression line.

### Dependencies
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

### Usage
1. Ensure that the "insurance.csv" file is present in the same directory as the Jupyter Notebook.
2. Open the Jupyter Notebook file.
3. Run each cell sequentially to execute the code.

### Results
- The code loads the insurance data and displays the first few rows using print(ins_data.head()).
- It also provides descriptive statistics of the dataset using print(ins_data.describe()).
- The scatter plot shows how age affects insurance costs using the scatter function from Matplotlib.
- The linear regression model is fitted using the LinearRegression class from Scikit-learn.
- The model is plotted alongside the scatter plot to visualize the linear regression line.
- Finally, an age value of 25 is predicted, and the corresponding insurance cost is displayed using model.predict(unk_x).
