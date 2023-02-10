# Surfs_Up


Overview

The purpose of this analysis is to review a dataset of weather conditions stored in a SQLlite database to provide data-driven insight to convince an investor to invest in opening up a Surf n' Shake shop in Hawaii.  The investory is hesistant due to a poor investment in a similar business that failed due to poor weather conditions that deterred business.  We need to provide statistical analytics specifically on the weather conditions in Hawaii that will convince the investory that the Surf n' Shake shop will be a profitable business venture.  We used SQLAlchemy to connect and generate queries to pull the necessary information needed for analysis, in order to explore the data in the SQLlite database. We used Jupiter notebook to import dependencies and create the commands to pull the data from the SQLite database in this module analysis.


Results

I first looked at the precipitation for a one year timeframe and reviewed the activity from August 23,2016-August 23, 2017 when we pulled the data.  As a result, I noticed that Oahu was mostly sunny throughout the day and experienced low levels of rainfall. 

Another thing I looked at was the number of weather stations actively collecting data on levels of precipitation and focused on the one station that had the most observations recorded.  In total, there were nine stations with USC00519281 showing the highest amount of observations at 2,772 entries.  We use the information from this station to review the temperature for the same time period.  The results showed that the average temperature throughout the year was 72 F with a low 54 F and a high of 85 F.

Finaly, I expanded our results to look at all of the observations that were recorded in the month of June and December regardless of the year.  The average temperature was in the 70s F.  Both June and December showed similar min/max and average temperatures.  The assumption is that the temperature does not have dramatic fluctuations throughout the year.


Summary

The temperature in Oahu is relatively the same throughout the year and the chances of continuous rainfall is low.  When I rewrite the queries to add precipitation to the results for June and December, the average precipitation in those months showed that June was 14% and December was 22%.  The precippitation and temperature proves that investing in Surf n'Shake is a good business venture and Oahu, Hawaii is the ideal location.
