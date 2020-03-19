### TO BAY AREA URBANSIM

## Overview
This foilder contains the regional output files for Bay Area UrbanSim 

## Files Setup
* [Household Control Totals](https://github.com/BayAreaMetro/bayarea_urbansim/blob/master/data/household_controls.csv): This table represents the total number of households forecast to live in the Bay Area in each forecast year. This means BAUS will ensure that its forecast conforms to these numbers. The values area counts of households. The values are segmented into 5-year intervals (2010 to 2050) and into four categories of approximate household income quartiles. 
* [Employment Control Totals](https://github.com/BayAreaMetro/bayarea_urbansim/blob/master/data/employment_controls.csv): This table represents the total number of jobs forecast to exist in the Bay Area in each forecast year. This means BAUS will ensure that its forecast conforms to these numbers. The values area counts of jobs. The values are segmented into each 5-year intervals (2010 to 2050) and into six sectors.
* [Additional Regional Control Totals](https://github.com/BayAreaMetro/bayarea_urbansim/blob/master/data/regional_controls.csv): This table provides additional forecast information that is passed on to the Travel Model. THe final column is the expected

## Scenarios
Each folder contains the ** output files for use in BAUS:
* s20: No Project (Plan Bay Area 2050)
* s21: Blueprint Basic
* s22: Blueprint Plus
* s23: Blueprint Plus Crossing
