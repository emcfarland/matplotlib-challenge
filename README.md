# matplotlib-challenge

This script takes two data sources from a clinical study on mice and visualizes the results in several ways. It should demonstrate competence in pandas, matplotlib, and scipy.stats.

After duplicate data is removed, summary statistics are run for the tumor volume of mice in the ten different drug trials.

Because the instructions were unclear, two sets of bar charts are produced--one set for unique mice per trial, and one set for total datapoints per trial. Each set has two identical bar charts, one produced with pandas and one produced with matplotlib.

Similarly, two identical pie charts are created using the prescribed methods to show the distribution of male and female mice in the study.

A new column created in the dataframe stores the final tumor volume for each mouse. Those volumes are then matched as lists to the names of their corresponding drug regimens. A loop through the dictionary keys and values returns quartile info and outliers for each drug. That dictionary is used to then make a box plot for each drug's final tumor volumes.

Next, a mouse from the Capomulin regimen is chosen at random. Its tumor volume over time is displayed with a line plot.

Last, tumor volume and weight data for all mice in the Capomulin regimen are taken and plotted on a scatter plot. A linear regression is performed and its line is overlaid.

Observations about the study can be found at the end of the script.
