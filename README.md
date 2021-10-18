# Py-Ber_Analysis by Ben Alshuler

## Overview
This project provides the PyBer administrative team with an insightful plethora of Dataframes and tables. Pandas converts their static CSV data from January to May 2019 into a more malleable Dataframe object. Then, with Matplot lib we created several charts culminating in a great summary line chart that plots the PyBer fare data by type of city. 

## Results
![Summary](analysis/PyBer_fare_summary.png?raw=true "PyBer Fare Summary")

This multiple line chart plots total fares for urban, suburban, and rural cities by week from January to May 2019. Obviously, PyBer relies heavily on fares collected from urban cities, with rural fares making up less than 10% of total fares. However, urban and suburban fares seem more elastic than rural fares; notice the sharp drops in April and May? We still need more data from rural drivers and rides to make any strong statements. 

### Summary


![Summary](analysis/PyBer_Sum_Table.png?raw=true "PyBer Fares by City Type")

Going forward, PyBer should expand the Dataframe with more ride data. A small snapshot like this is useful, but a larger set of data will only help shed more light on what strategies will ensure growth and stable service (and in which markets). PyBer could also expand its data collection to note rider demographics. We also did not stratify the data by external factors like special events in given cities. Weather, holidays, gas prices, et cetera could all influence our data. Controlling for these factors and analyzing their effects would greatly augment any future work. 

Finally, future analysis could incorporate reviews of drivers, and identify what traits or working conditions influence retention of PyBer customers and workers. Do these factors vary geographiclly? Socioeconomically? 
