# Matplotlib-challenge3
* Imported dependencies and setup, then merged the files together into a single dataset
* Dropped duplicate rows, which were associated with mouse g989
* Generated summary statistics based on drug regimen and mean, median, variance, standard deviation, and standard error of the mean
* Bar and Pie charts:
    * Created a new dataframe and used value counts to calculate data points
    * Generated bar charts using pandas and by manually creating lists for matplotlib to chart
    * Repeated the steps, with alterations for a pie chart and for grouping by Male/Female value counts
* Quartiles, Outliers, Boxplots:
    * Created a new dataframe grouped by mouse ID and maximum timepoint
    * Merged the dataframe with the other data
    * Created a for loop for the list of four drugs. Created an empty list to store the information in for each of the four drugs.
        * Within the for loop, calculated the quartile information
        * After running through the loop, the tumor volumne list was filled with information on the tumor volumes, separated by each drug group
        * Made the outlier green to make it stand out
* Line and Scatter Plots
    * Separated data so that it only had data on Capomulin
    * Chose mouse f966
    * Made a dataframe using tiempoint and tumor volume, then made a line graph off of the data
    * Scatter plots:
        * Created variables for calculating average weight and tumor size
        * Generated scatter plots off of this information
        * Used the dataframe to calculate the correlation coefficient and regression