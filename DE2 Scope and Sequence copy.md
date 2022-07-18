 
# DE 2 Component Skills

## Working with data in Python I

### TLO: Use python for basic data description, loading, manipulation, and analysis  

#### Transforming pandas DataFrames

#### ELOs:
    - Understand and use pandas tools to inspect DataFrames  
    - Perform fundamental manipulations: sorting rows, subsetting, and adding new columns.

    Inspecting a DataFrame
    Parts of a DataFrame
    Importing data: CSV to DataFrame
    Sorting and subsetting
    Sorting rows
    Subsetting columns
    Subsetting rows
    Subsetting rows by categorical variables
    New columns
    Adding new columns
    Bringing it all together- analysis requiring all this

#### Aggregating DataFrames

#### ELO
    - Calculate summary statistics on DataFrame columns, grouped summary statistics, and pivot tables.

    Summary statistics
    Mean and median
    Summarizing dates
    Cumulative statistics
    Counting
    Dropping duplicates
    Counting categorical variables
    Grouped summary statistics calculations
    Calculations with .groupby()
    Multiple grouped summaries
    Pivot tables
    Pivoting on one variable
    Fill in missing values and sum values with pivot tables


#### Slicing and Indexing DataFrames

#### ELO
    - Combine indexes with slicing to subset DataFrames appropriately to serve analysis goals.

    Explicit indexes
    Setting and removing indexes
    Subsetting with .loc[]
    Setting multi-level indexes
    Sorting by index values
    Slicing and subsetting with .loc and .iloc
    Slicing index values
    Slicing in both directions
    Slicing time series
    Subsetting by row/column number
    Working with pivot tables
    Pivot temperature by city and year
    Subsetting pivot tables
    Calculating on a pivot table

## Creating and Visualizing DataFrames
Learn to visualize the contents of your DataFrames, handle missing data values, and import data from and export data to CSV files.

    Visualizing your data
    single variable, static analysis example
    single variable over time analysis example
    multiple variables, static analysis example
    multiple variables over time analysis example
    Missing values
    Finding missing values
    Removing missing values
    Replacing missing values
    Creating DataFrames
    List of dictionaries
    Dictionary of lists
    DataFrame to CSV



# matplotlib

## Introduction to Matplotlib

Introduction to data visualization with Matplotlib

Using the matplotlib.pyplot interface

## Quantitative comparisons and statistical visualizations
Visualizations can be used to compare data in a quantitative manner. This chapter explains several methods for quantitative visualizations.

    Quantitative comparisons: bar-charts
    Bar chart
    Stacked bar chart
    Quantitative comparisons: histograms
    Creating histograms
    "Step" histogram
    Statistical plotting
    Adding error-bars to a bar chart
    Adding error-bars to a plot
    Creating boxplots
    Quantitative comparisons: scatter plots
    Simple scatter plot
    Encoding time by color



## Customizing your graphs
    Adding data to an Axes object
    Customizing your plots
    Customizing data appearance
    Customizing axis labels and adding titles
    Small multiples
    Creating a grid of subplots
    Creating small multiples with plt.subplots
    Small multiples with shared y axis


## Plotting time-series

Time series data is data that is recorded. Visualizing this type of data helps clarify trends and illuminates relationships between data.
Plotting time-series data
Read data with a time index
Plot time-series data
Using a time index to zoom in
Plotting time-series with different variables
Plotting two variables
Defining a function that plots time-series data
Using a plotting function
Annotating time-series data
Annotating a plot of time-series data
Plotting time-series: putting it all together


## Sharing visualizations with others

ELO
    - Save your figures as files
    - Adjust figures' look and feel
    - Automate figures' creation based on input data


    Preparing your figures to share with others
    Selecting a style for printing
    Switching between styles
    Saving your visualizations
    Saving a file several times
    Save a figure with different sizes
    Automating figures from data
    Unique values of a column
    Automate your visualization





## Working with data in Python II

## TLO: Use python for data gathering, cleaning, ...



numpy
seaborn
TLO - Joining & Importing Data
Joining Data with pandas
Import data into Python from all types of flat files, and customize imports.
Importing data from the Internet
Interacting with APIs to import data from the web
Cleaning data
Common data problems
Text and categorical data problems
advanced data cleaning problems




#### Classification
#### ELO
    - Understand the use and purpose of classification 
    - Use scikitlearn to perform common supervised learning techniques
    - Employ fundamental concepts in classification to conduct an analysis.

Supervised learning
Which of these is a classification problem?
Exploratory data analysis
Numerical EDA
Visual EDA
The classification challenge
k-Nearest Neighbors: Fit
k-Nearest Neighbors: Predict
Measuring model performance
The digits recognition dataset
Train/Test Split + Fit/Predict/Accuracy
Overfitting and underfitting


#### Regression
#### ELO: 
- Regression - What is it good for 
- Employ fundamental concepts in regression to predict X for Y data.


Introduction to regression
Which of the following is a regression problem?
Importing data for supervised learning
Exploring the Gapminder data
The basics of linear regression
Fit & predict for regression
Train/test split for regression
Cross-validation
5-fold cross-validation
K-Fold CV comparison
Regularized regression
Regularization I: Lasso
Regularization II: Ridge

#### Fine-tuning your model
#### ELO:
    - Evaluate model performance using metrics available in scikit-learn 
    - Optimize your classification and regression models using hyperparameter tuning


How good is your model?


Metrics for classification


Logistic regression and the ROC curve


Building a logistic regression model


Plotting an ROC curve


Precision-recall Curve


Area under the ROC curve


AUC computation


Hyperparameter tuning


Hyperparameter tuning with GridSearchCV


Hyperparameter tuning with RandomizedSearchCV


Hold-out set for final evaluation


Hold-out set reasoning


Hold-out set in practice I: Classification


Hold-out set in practice II: Regression


#### Preprocessing and pipelines
0%
This chapter introduces pipelines, and how scikit-learn allows for transformers and estimators to be chained together and used as a single unit. Preprocessing techniques will be introduced as a way to enhance model performance, and pipelines will tie together concepts from previous chapters.


Preprocessing data


Exploring categorical features


Creating dummy variables


Regression with categorical features


Handling missing data


Dropping missing data


Imputing missing data in a ML Pipeline I


Imputing missing data in a ML Pipeline II


Centering and scaling


Centering and scaling your data


Centering and scaling in a pipeline


Bringing it all together I: Pipeline for classification


Bringing it all together II: Pipeline for regression





