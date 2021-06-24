# Wine-Quality-Prediction-Regression
## Project Description 
This project is for predicting quality of wines using various regression methods. The purpose of this was to get familiar with workflow in a typical machine
learning problem, use some exploratory data analysis, preprocess data, use hyperparameter selection method, implement k-fold cross validatiaon technique and use regression 
algorithms viz. LASSO regression, random forest regression and support vector regression. All the ML algorithms are implemented using in built functions from scikit learn library in python. All code is present in a single jupyter notebook "code.ipynb" file.

## Data
Data used for this project is taken from Wine Quality Data Set at UCI ML repo https://archive.ics.uci.edu/ml/machine-learning-databases/wine-quality/winequality-white.csv
If you run the code script then data is downloaded in the current directory on the fly so there is no need to externally download data. However it can be found in the data folder or can be downloaded from the given link.

## Exploratory Data Analysis
1. Checked if there are any missing values in the data (no missing data), found range for each column in the csv file.
2. Histograms of each column to get an idea of their distribution.
3. Scatter plot and correlation matrix for each pair of data to see if any features are highly correlated (if high correlation is found then some features can be eliminated)

## Preprocessing Data
1. Train test split(80:20)
2. Training data is normalized using standard scaler from sklearn preprocessing module. Same transformation is applied to testing data also.


## Hyperparameter selection
1. Grid search over range of given hyperparameters along with k-fold cross validation is used to select the best hyperparametrs.

## Models tried
1. Lasso regression
2. Random forest regression
3. Support vector regression

## Note: 
If you are trying to run the code in your system then make sure all required libraries and data files are present. ALternatively the notebook code.ipynb can be directly
uploaded and run on google colab server without any additional installation.
