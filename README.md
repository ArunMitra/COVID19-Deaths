# COVID-19 Deaths in the USA - A heart-wrenching story of who bears the toll
A quick analysis of COVID19 deaths in the USA by state, age group, ethnicity/race; considering USA census data 


## The question: 
  ### If this horrible virus does not discriminate based on state, ethnicity/race or age should we not see the death toll spread out evenly across these groups?

## The data: 
  - Deaths data from *Health.gov* (https://healthdata.gov/dataset/deaths-involving-coronavirus-disease-2019-covid-19-race-and-hispanic-origin-group-and-age) 
  - Population estmates data from *Center for Disease Prevention* (https://wonder.cdc.gov/wonder/help/bridged-race.html#About%201990-2018)
  
## EDA Issues:
  - Mismatched Ethnicity/Race groupings in the 2 datasets
  - Mismatched Age Groups in the 2 datasets
  - New York City data included in the states tables (in addition to New York State)
  - Little or no valid data for minors (due to confidentiality issues)
  - No data for Puerto Rico
  
## Findings
  - New York, New Jersey and Massachusets have the biggest fatalities, California is 6th.
  - Unexpectedly, New York, New Jersey and Massachusets also have the highest fatalities per million of population, California is not as bad at 28th.
  - Death toll sloped down steadily across the age groups with Seniors suffering the biggest toll, both in absolute terms and in deaths per million
  - Whites paid the biggest toll in absolute number of deaths. Blacks, Hispanic/Latinos, Asians and American Indians / Alaskan Natives followed in that order
  - Per million, the order was Blacks (by far), then Whites, Hispanics/Latinos, American Indians / Alaskan Natives, and Asians in that order
  - Comparing working age adults (25-64) to seniors (65+), Americas seniors have paid a terrible price, both in absolute numbers and in per Million terms

## Hypotheses Tested and results: 

**Null Hypothesis**: There is no difference in COVID-19 fatality rates between **Blacks** and **Whites** in the USA

z-test p-value = 0 : *Null Hypothesis Rejected*

**Null Hypothesis**: There is no difference in COVID-19 fatality rates between **Hispanics/LatinXs** and **Whites** in the USA

z-test p-value = 0 : *Null Hypothesis Rejected*

**Null Hypothesis**: There is no difference in COVID-19 fatality rates between **Blacks** and **Hispanics/LatinXs** in the USA

$z-test p-value = 0 : *Null Hypothesis Rejected*

**Null Hypothesis**: There is no difference in COVID-19 fatality rates between **Asians** and **American Indian/Alaskan Natives** in the USA

z-test p-value = ? : (Results pending)

**Null Hypothesis**: There is no difference between COVID-19 fatality rates between **Working age adults** and **Seniors** in the USA

z-test p-value = 0 : *Null Hypothesis Rejected*

## Future questions: 
Going forward, with the recent spikes in the southern/south-western states, is the disproportionate toll on Seniors, Blacks and Hispanics/LatinXs going to continue, despite increased public and government understanding of the above trends?

## An apology: 
I apologize, if despite my best efforts, the terminology used to refer to the various race/ethnic groups, and my segmentation choices, are insensitive to anyone. I welcome any feedback that would help to make me be better informed about this.
