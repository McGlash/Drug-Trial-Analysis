# Matplotlib Challenge - The Power of Plots

## Background

![Laboratory](Images/Laboratory.jpg)

I analyzed data from an (hypothetical) animal study. In the study, 249 mice identified with SCC tumor growth were treated through a variety of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of the drug of interest, Capomulin, versus the other treatment regimens. 

I generated tables, figures (using Matplotlib and Pandas) and a top-level summary of the study results.

## Approach

* Cleaned the data

* Used the cleaned data for the remaining steps.

* Generated a summary statistics table consisting of the mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.

* Generated a bar plot showing the number of total mice for each treatment regimen throughout the course of the study.

* Generated a pie plot that shows the distribution of female or male mice in the study.

* Calculated the final tumor volume of each mouse across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Calculated the quartiles and IQR and quantitatively determine if there are any potential outliers across all four treatment regimens.

* Using Matplotlib, generated a box and whisker plot of the final tumor volume for all four treatment regimens and highlight any potential outliers in the plot by changing their color and style.

* Selected a mouse that was treated with Capomulin and generate a line plot of time point versus tumor volume for that mouse.

* Generated a scatter plot of mouse weight versus average tumor volume for the Capomulin treatment regimen.

* Calculated the correlation coefficient and linear regression model between mouse weight and average tumor volume for the Capomulin treatment. Plot the linear regression model on top of the previous scatter plot.
