# DataMining
Data Mining Proyect - Classifiers
This is a python data mining proyect, that contains an ensemble learning method for classification with 3 different classifiers.
## Process
The code will be divided into __6 different development levels__
1. Data Analysis
    1. Data retrieve
    2. Plotting the data (Histograms and Plots)
    3. Outliers detection
2. PCA
    1. Reading the data from the file
    2. Creating the [PCA](https://builtin.com/data-science/step-step-explanation-principal-component-analysis).
    3. Printing the variance 
    4. Ranking the attributes by their loadings in the principal components
3. Classification models and cross validation
    1. Reading the data from the file
    2. Train the models and test them with a Stratified Cross-Validation
    3. Train the models and test them with a Normal Cross-Validation
    4. Train the models and test them with a Stratified Cross-Validation with Standardized Data
    5. Train the models and test them with a Normal Cross-Validation with Standardized Data
    6. Train the models and test them with a Stratified Cross-Validation with PCA transformed data
    7. Train the models and test them with a Normal Cross-Validation with PCA transformed data
4. Creating the Ensemble learning method
    1. Reading the data from the file
    2. Turning data into PCA
    3. Train the models and test them with a Normal Cross-Validation
    4. Testing the ensemble with Normal Cross-Validation
    5. Testing the ensemble with Stratified Cross-Validation
    6. Plotting ensemble's decision boundaries
    7. Measuring the Logarithmic loss
5. Plotting the results
    1. Creating a class for the Ensemble and its methods
    2. Setting the ensemble's parameters
    3. Plotting the classification reports
    4. Plotting the confusion matrix
    5. Plotting the scatterplot of the classification results
6. Final Project
    1. Reading the data from a given file file, set up the ensemble parameters, transform the data by applying the PCA and train the models
    2. The 2-dimensions PCA plot
    3. The Variance explanation
    4. The cross validation test results per fold
    5. The ensemble's decision boundaries
    6. The ensemble's confussion matrix
    7. The scatter plot of the classification results
## Getting Started
### Prerequisites
- Anaconda or Python 3.7 or > 3.7
- Jupyter Notebook
- Orange3 Data Mining App library
- Matplolib, numpy, pandas, yellowbrick, seaborn, mlxtend python libraries
### Install
- To install Pandas library
```
python -m pip install wheel
python -m pip install pandas
```
- To install Matplotlib library
```
python -m pip install matplotlib
```
- To install Numpy library
```
python -m pip install numpy
```
- To install Orange3 library
[Link to install Orange3 Library](https://github.com/biolab/orange3)

- To install Yellowbrick
[Link to install Yellobrick](https://www.scikit-yb.org/en/latest/quickstart.html)

- To install Seabron
[Link to install Seaborn](https://seaborn.pydata.org/installing.html)

- To install Mlxtend
[Link to install Mlxtend](http://rasbt.github.io/mlxtend/installation/)

### Deployment
1. Download or copy the repository .
2. Open the terminal and move to the folder location where the proyect is stored.
3. Run the Notebook environment
```
python -m notebook
```
4. It should open the Jupyter Environment on the browser, then click on the .ipynb file that you prefer
5. Run the proyect by clicking the **>>** button and press **Clear Cells and Re-Run the proyect**
## Built With
  - Python 3.7 (Anaconda)
  - Jupyter Notebook
## Authors
 __- Omar Garduza__ - _Initial Work_ - [OmarGard](https://github.com/OmarGard)
