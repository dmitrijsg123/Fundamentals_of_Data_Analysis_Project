# Fundamentals_of_Data_Analysis_Project<br>

## Simple Linear Regression Model using Python

The aim of the project is to build a Simple Linear Regression to study if there is a statistically important linear correllation between WIND SPEED and WIND TURBINE POWER OUTPUT. The goal is to accurately predict turbine power output from wind speed. The data can be used in the wind power industry to predict the necessary amount of wind power production.

Linear Regression<br>
Linear Regression is a statistical technique which is used to find the linear relationship between dependent and one or more independent variables. It is applied for learning Regression problems where we can try and predict a continuous variable.

Linear Regression can be further classified into two types – Simple and Multiple Linear Regression. In this project we employ Simple Linear Regression technique where we have one independent and one dependent variable. It is the simplest form of Linear Regression where we fit a straight line to the data.

Structure of the project<br>
Initial idea of the project wasd to divide it into 3 main parts:<br>
1. What is Simple Linear Regression?<br>
Its importance and implementation.<br>
Maths behind the Simple Linear Regression.<br><br>

2. Building Simple linear Regression in Python<br><br>

3. Checking accuracy of the model.<br>
Comparison of the Simple Linear Regression model with other Linear Regression models.<br>

we enlarged the project a little bit during the work and in the end it has 8 sections.<br>
1. 1. What is Simple Linear Regression?<br>
Its importance and implementation.<br>
Maths behind the Simple Linear Regression.<br><br>

2. Simple Linear Regression plotting in Python.<br>
2.1 DataFrame Scatterplot.<br>
2.2 Simple Linear Regression modelling with sklearn.<br>

3. Dataset values validity evaluation.<br>
In that section we allow ourselves to question validity of some of the dataset values and manipulate with the dadaset by excluding some of them.<br>

4. Analyzing the prediction<br>
4.1 Coefficient of the line (slope).<br>
4.2 Intercept. <br>
4.3 Coefficient of determination (r squared).<br>
4.4 Pearson's correlation coefficient r.<br>
In Section 4 we analyze the efficacy of the prtediction model by looking at some of its important parameters.<br>

5. Eliminating zero y values at the beginning and at the end of the dataset.<br>
Here we manipulate with the dataset again by excluding more questionable values.<br>

6. Analyzing separate segments of the dataset.<br.
Here we break the dataset into separate segments and compare them.<br>

7. Train and test split method.<br>
8. Simple Linear Regression versus Multiple Linear Regression versus Polynomial Linear Regression.
In the last section we question precision of the Simple Linear Regression model in relation to our dataset and compare it with Multiple and Polynomial Regression.<br>

Libraries<br>
The main program used for the project is Anaconda which is installed on my computer. The work is done with Jupyter Notebook. The Python libraries used in this project are:
• Pandas – It provides tools for data storage, manipulation and analysis tasks.<br>

• Numpy – It provides a fast numerical array structure and operating functions.<br>

• Matplotlib – It is the basic plotting library in Python. It provides tools for making plots.<br>

Seaborn - Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics. <br>

• Scikit-Learn – The required machine learning library in Python.

Added files: As well as the main project file Powerproduction.ipynb and powerproduction.csv file, there are powerproduction2.csv and powerproduction3.csv files with manipulated datasets, as well as "Roughwork_datasets.ipynb" file that contains some plots. We decided not to include it into our final version of the project and, thus, left it outside of tyhe main file.<br>

REFERENCES: All the sections of the project are fully referenced (usually references are at the end of each section).