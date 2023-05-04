# 05-Module-Pymaceuticals-Challenge
Week 05 Challenge - Matplotlib


### Analysis
Study of 249 mice with squamous cell carcinoma and the effect that different drug treatments have on their tumors. <br><br><br>

### Preparing the data:
Called python dependancies and merge data from two different sources into a single data frame.
Identified and removed duplicate data and created a new dataframe with all unique data and proceeded to build a statistics summary of the Tumor Volume for the different drug regimens in the data. <br><br><br>

### Create Bar Charts and Pie Charts
Found the count of timepoints per drug regimen and created a bar chart to visualize the data. The same chart was created twice using pandas and using pyplot.
 <br><br>
Calculated the total male mice and total female mice and created a pie chart to visualize the data labeled with the percentage of each sex. The same chart was created twice using pandas and using pyplot <br><br><br>

### Calculate Quartiles, Find Outliers, and Create a Box Plot
Calculated the greatest timepoint for each mouse and merged the data with the original dataframe to creat a new dataframe to only data related to the greatest timepoint for each mouse.
The efficacy of four different treatemnts ("Capomulin", "Ramicane", "Infubinol", and "Ceftamin") within the data will be analyzed and compared. They were stored in a list for use in a for loop.
Tumor volumes will be used for plotting the data further in the analysis and therefore a list was created using a for loop to store this data.
 <br><br>
For loop was utilized to calculate the lower quartile, interquartile, upper quartile, lower bounds and upper bounds of each drug treatment.
Another for loop then checks each drug treatment for outliers and prints the results.
 <br><br>
a box plot is generated to compare the four drug treatments and visualize their respective quartile ranges and any identified outlier(s). <br> <br> <br>


*"Quartiles, Outliers and Boxplots" section was a collaborative effort with Mario Martinez*<br><br><br>


### Line and Scatter Plots
Retrieved the tumor volume and timepoint data for a single mouse under the Capomulin regimen only and generated a line plot using matplotlib.<br><br>

Matplotlib was again used to generate a scatter plot for mouse weight vs. average  tumor volume for only the Capomulin regimen.<br><br><br>

### Correlation coeffand Regression
Calculated the correlation coefficient and linear regression  for weight vs average tumor volume for only the Capomulin regimen.<br> <br> <br><br><br> <br> <br><br>
###
*"Quartiles, Outliers and Boxplots" section was a collaborative effort with Mario Martinez*