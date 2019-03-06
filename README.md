In this project we will apply multiple linear regression to a hydrologic datasetPreview the document. 
To get started, look at the Project helps page.

This data deals with baseflow (Links to an external site.)Links to an external site.. 
Each row corresponds to one data point (a river segment during one month). The columns are:

Date – number of days since 01/01/0000
Segment id – an identifier of the segment of river; it can be treated as a categorical variable
x/y – the spatial location of the gaging station at which observations are obtained
Evapotranspiration (Links to an external site.)
Links to an external site. – the evapotranspiration amount of an area adjacent to the river segment in the given month
Precipitation - the precipitation amount of an area adjacent to the river segment in the given month
Irrigation pumping - the amount of groundwater pumped out for irrigation in an area adjacent to the river segment in the given month
Observed – observed baseflow
The target variable is Observed. We want to use linear regression to predict what the baseflow will be.

The task is to experiment with linear regression on this dataset and see what kind of Rsquared and p values you get. 
Look at the dataset as a whole and also at each river segment individually. Do they give different results with linear regression? 
If so, why? Which are the most predictive explanatory variables? Why? Be sensitive to p-hacking in your analysis.
