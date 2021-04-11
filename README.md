# Matplotlib Analysis

This repository features Python analysis using the Matplotlib library to visualize data in various plots. 

Three major observations are included at the top of notebook.

![Here are the results](https://github.com/lmfao415/Matplotlib-challenge/blob/main/data/Screenshot%202021-04-11%20153234.png?raw=true)

The complete Jupyter Notebook contains all of the following:

* Checks the data for any mouse ID with duplicate time points and removse any data associated with that mouse ID.

* Generates a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generates a bar plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows  the number of total mice for each treatment regimen throughout the course of the study.

* Generates a pie plot using both Pandas's `DataFrame.plot()` and Matplotlib's `pyplot` that shows the distribution of female or male mice in the study.

* Calculates the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculates the quartiles and IQR and quantitatively determines if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generates a box and whisker plot of the final tumor volume for all four treatment regimens and highlights any potential outliers in the plot by changing their color and style.

* Selects a mouse that was treated with Capomulin and generate a line plot of tumor volume vs. time point for that mouse.

* Generates a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculates the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plots the linear regression model on top of the previous scatter plot.
