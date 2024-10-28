# Pymaceuticals-Challenge
Module 5 Challenge

In this challenge, a pharmaceutical company that specializes in anti-cancer medications recently began screening for potential treatments for squamous cell carinoma (SCC), which is a commonly occurring form of skin cancer. The company has given access to the complete data from their most recent animal study.

In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

This assignment is broken down into the following tasks:
Prepare the data.
Generate summary statistics.
Create bar charts and pie charts.
Calculate quartiles, find outliers, and create a box plot.
Create a line plot and a scatter plot.
Calculate correlation and regression.

To prepare the data, the dependency and data imports were run before merging the mouse_metadata and study_results DataFrames into a single DataFrame.
Next the number of unique mice IDs in the data are displayed, then checked for any mouse ID with duplicate time points. Next, the number of unique mice IDs in the data are displayed. Display the number of unique mice IDs in the data, then checked for any mouse ID with duplicate time points. Finally, the data associated with that mouse ID is displayed, and a new DataFrame (where this data is removed) is created and used for the remaining steps. 

To generate summary statistics, a DataFrame of summary statistics is created, which includes a row for each drug regimen with names contained in the index column. Additionally, a column is created for each of the following statistics: mean, median, variance, standard deviation, and SEM of the tumor volume.
The updated number of unique mice IDs is displayed. 

Creating bar charts and pie charts: Both charts are identical and show the total total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study.
The first bar chart is created using the Pandas DataFrame.plot() method and the second bar chart was created with Matplotlib's pyplot methods.
Both pie charts are identical and show the distribution of unique female versus male mice in the study.
The first pie chart was created with the Pandas DataFrame.plot() method and the second pie chart was created with Matplotlib's pyplot methods.

Calculating quartiles, finding outliers and creating the box plot: 
The final tumor volume of each mouse was calculated across four of the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin. Next the quartiles and IQR were calculated, and whether there are any potential outliers across all four treatment regimens was determined.
To display the results of this data, Matplotlib was used to generate a box plot that shows the distribution of the final tumor volume for all the mice in each treatment group, highlighting any potential outliers in the plot by changing their color and style.

Creating the line and scatter plots:
A single mouse that was treated with Capomulin was selected to generate a line plot of tumor volume versus time point for that mouse.
Next, a scatter plot of mouse weight versus average observed tumor volume for the entire Capomulin treatment regimen was generated using Matplotlib.

To calculate the correlation and regression, the correlation coefficient and linear regression model were used to do the calculation between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.
Following the calculation, the linear regression model was plotted on top of the previous scatter plot.

For this challenge, help was sought using ChatGPT when using the linear regression model. 
