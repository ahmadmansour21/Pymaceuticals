# Pymaceuticals

The code for this assignment can be found in the Pymaceuticals-code folder which is located in the Pymaceuticals folder in the Pymaceuticals repository on Github

The code for this challenge was formulated with the help of past class activities' solutions on Gitlab as well as the Xpert Learning Assistant AI tool.

The first portion of the assignment involves the use of basic pandas functions to visualize the data - pd.read_csv(), pd.merge() - and to clean the data.

The Summary Statistics portion of the assignment involved the use of the groupby() function to calculate the mean, median, stdv, variance and sem of the cleaned up dataframe. This process was made much quicker with the use of the agg() function alongside groupby().

The Bar and Pie charts section involved the use of pandas and matplotlib to produce bar and pie charts of information from the dataset - this section aimed to emphasize the two different methods available for producing such graphs.

The Quartiles, Outliers and Boxplots section involved the use of groupby() and max() functions to find the maximum timepoints for each regimen, followed by identification of outliers. The identification of outliers was made possible with the calculations of the first quartile and third quartile in order to calculate iqr. Once done, iqr was used the determine the upper and lower values of the datasets. Finally, outliers were identified by comparison to these upper and lower values. Seeing as there were multiple treatments, a for loop was used to cycle through the data and identify the tumor volumes for each of these treatments. In doing so, we were able to calculate the upper and lower values of the tumor volumes for each treatment, allowing the identification of outliers.

The Line and Scatter plots section was an exercise to be able to generate the mentioned plots using plt.line and plt.scatter for one specific mouse receiving one specific treatment. Thus, this required us to access the relevant information for that particular mouse/treatment using the loc function to access the drug regimen column and define it as that treatment and then the Mouse ID column to define it as that particular mouse.

The final section was an exercise to figure out how to calculate the correlation for the previous scatter plot as well as how to set the regression line for that previous scatter plot.