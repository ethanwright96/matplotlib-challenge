# matplotlib-challenge
# Pymaceuticals, Inc. - Clinical Study Analysis

## Background
You've recently joined Pymaceuticals, Inc., a pharmaceutical company specializing in anti-cancer medications. The company has been conducting an animal study to screen potential treatments for squamous cell carcinoma (SCC), a common form of skin cancer. The study involved 249 mice with SCC tumors, which received different drug regimens. The goal was to compare the performance of Pymaceuticals' drug of interest, Capomulin, against other treatment regimens.

As a senior data analyst, you've been granted access to the complete data from the study. Over a period of 45 days, tumor development was observed and measured for the mice. Your task is to generate all the necessary tables and figures for the technical report of the clinical study. Additionally, the executive team expects a summary of the study results.

## Instructions

### Prepare the Data
- Merge the `mouse_metadata` and `study_results` DataFrames into a single DataFrame.
- Check for any duplicate mouse IDs and time points.
- Remove the data associated with the duplicate mouse ID to obtain a cleaned DataFrame.
- Display the number of unique mouse IDs in the cleaned data.

### Generate Summary Statistics
- Create a DataFrame containing summary statistics for each drug regimen.
- Include statistics such as mean, median, variance, standard deviation, and SEM of the tumor volume.
- Use any appropriate method to generate these statistics.

### Create Bar Charts and Pie Charts
- Create two identical bar charts showing the total number of mouse ID/Timepoints for each drug regimen.
- Use both Pandas' DataFrame.plot() method and Matplotlib's pyplot methods to create the bar charts.
- Create two identical pie charts displaying the distribution of female and male mice in the study.
- Use both Pandas' DataFrame.plot() method and Matplotlib's pyplot methods to create the pie charts.

### Calculate Quartiles, Find Outliers, and Create a Box Plot
- Calculate the final tumor volume for each mouse across the most promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
- Calculate the quartiles and interquartile range (IQR) to determine if there are any potential outliers in the four treatment regimens.
- Use Matplotlib to generate a box plot showing the distribution of the final tumor volume for all mice in each treatment group.
- Highlight any potential outliers in the plot.

### Create a Line Plot and a Scatter Plot
- Select one mouse treated with Capomulin and generate a line plot of tumor volume versus time point for that mouse.
- Create a scatter plot of mouse weight versus the average observed tumor volume for the entire Capomulin treatment regimen.

### Calculate Correlation and Regression
- Calculate the correlation coefficient and the linear regression model between mouse weight and average observed tumor volume for the Capomulin treatment regimen.
- Plot the linear regression model on top of the scatter plot.

### Submit Your Final Analysis

## Files
Download the following files to help you get started:
[Module 5 Challenge files](https://...link...)

*Note: Refer to the provided sample solution, "Pymaceuticals_starter.ipynb", for the desired format of the assignment.*
