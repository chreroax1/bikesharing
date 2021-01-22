<h1 align = "Center"> Bikeshare
</h1>

<p align = "center">
<img src = "https://d21xlh2maitm24.cloudfront.net/nyc/Transparent-Bike.png?mtime=20160420134420">
</p>
<br>

<h2> Overview of the analysis </h2>

The purpose of this project was to see if a bike rental business is worth investing in in the city of Des Moines, Iowa. Data from the city of New York during August 2018, I created visualizations to help illustrate some data points. 

<h2> Preparation </h2>
First, I needed to change a data type of the column ('tripduration') from reading as an integer into reading as timedate data. The purpose of this was so it could be broken down into hours, minutes and seconds. I did this by taking the csv file and converting the data into the proper data type using Junyper Notebook and Pandas software. Once converted, I exported the newly transformed csv into Tableau to start our visualizations.

<h2> Results </h2>
Using the data, here are some of the key points that were visualized:

* There were a total of 2,344,224 Citibike trips in the month of August in 2018.

* 1,900,359 of users subscribe to Citibike while there were 443,865 one time trip transactions.

* The average bike trip was approximately 5 hours, primarily occuring on weekdays between 7-9 AM and 5-7 PM.

* We are also able to see that Males (1,530,272 trips) are out numbering the Female renters by almost 3:1 (588,431).

* Therefore, Male subscribers are predominantly using Citibikes.

You can see the visualizations [here](https://public.tableau.com/profile/chris8347#!/vizhome/NYCCitibikeAnalysis_16112749956500/NYCCitibikeAnalysis?publish=yes).

<h2> Summary </h2>
There are some flaws noted about Des Moines transit system (DART) on numerous websites. The average wait times of 20-40 minutes and some areas being too far out for most transit lines, Des Moines residents could use an alternative to get around the city. I would recommend looking into weather data for the summer and winter months to see if this business is seasonal or if it can stay prosperous all year around. It would also be beneficial to see data from Des Moines residents to see if they would actually use the bike sharing service. That way, Citibike can place the stations in close proximity to customers that would use them.