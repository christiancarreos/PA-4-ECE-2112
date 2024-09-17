# PA-4-ECE-2112
### CARREOS, Christian Benedict R.

### Objectives:
Identify the codes and functions needed in cleaning and visualizing data
Apply and use the different codes and functions in creating a Python program that will
be used in data wrangling and data visualization



### Problem
ECE BOARD EXAM PROBLEM: Using data wrangling and data visualization technique with
storytelling, analyze the data and present different (i) data frames; and (ii) visuals using the dataset given.

### Create the following data frames based on the format provided:
Example: Vis = [“Name”, “Gender”, “Track”, “Math<70”]; hometown is constant as Visayas

a) Filename: Instru = [“Name”, “GEAS”, “Electronics >70”]; where track is constant as
Instrumentation and hometown Luzon

b) Filename: Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”]; where hometown is
constant as Mindanao and gender Female



### Expected Outputs:
ECE BOARD EXAM PROBLEM

The loaded board2.csv file with all the data.

A dataframe containing 'Name', 'Gender', 'Track', and 'Math'<70 from the csv file wherein the condition is that the Hometown is Visayas.

A dataframe containing 'Name', 'GEAS', 'Electronics'<70 from the csv file wherein the condition is that the Track is Instrumentation and the Hometown is Luzon.

A dataframe containing 'Name', 'Track', 'Electronics' and 'Average'>=55 from the csv file wherein the condition is that the Gender is Female and the Hometown is Mindanao.

A visualization (Bar Graphs) that shows how the different features contributes to average grade.



### Functions used
pd.read_csv() to load the dataset.

boardexam.loc to locate the data from the csv file given the conditions.

cars.tail() to display the last five rows.

.groupby splits the data into groups based on the values of specified columns.

.tight_layout() adjusts the layout of plots in a figure. It ensures that subplots and their labels, titles, and ticks do not overlap and are arranged properly within the figure.

.show() displays the plot or figure you have created. 

.mean() calculates the mean of data in a DataFrame.



### Visualizations
Average Grade by Track:

A bar plot showing the average grade for each academic track.

Average Grade by Gender:

A bar plot showing the average grade for each gender.

Average Grade by Hometown:

A bar plot showing the average grade for each hometown.
