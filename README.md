# Surfs_Up Analysis

## Project Overview
Analyze weather data from Oahu, Hawaii to provide information that will be used to determine the viability of opening a
year-round Surf 'n' Shake Shop.  The primary focus is analyzing the temperatures for the months of June and December.

## Results:
  _June vs December Temperatures_ 
 
 ![image](https://user-images.githubusercontent.com/90986041/141600378-01d8645a-d065-4632-8124-81f511d8cfe2.png)
 ![image](https://user-images.githubusercontent.com/90986041/141600444-0ae17984-2ad7-4fd0-be9c-b5ad550d8bb9.png)
  
The large number of counts for both June and December provide confidence and high credibility of the statistical results.
 * The average temperatures for each month are the same as the 50% percentiles, which indicates the results for both months 
    are not skewed.
 * The low standard deviations indicate the data is clustered near the mean.  December's data is slightly more spread out.
 * Oahu's temperatures in June and December are fairly consistent with only 4° between the monthly average temperatures. Not too
    surprising June's temperatures are slightly higher than December's.
  
 ### Additional Analysis:
  _June vs December Precipitation_
  
 The dataset also contained precipitation readings.  The graph below shows the stats for 12 months between 8/23/16-8/23/17:
 
   ![image](https://user-images.githubusercontent.com/90986041/141602773-c5e5a464-ba85-4105-955b-261ca920fa60.png)

 When the dataset is filtered to December, there are only eight readings.  The precipitation levels for December are much higher 
 than the annual readings above. Further research is needed to determine if December's results are accurate representations or 
 if there is missing data.
 
  ![image](https://user-images.githubusercontent.com/90986041/141600569-5e808167-0a94-4234-8d00-816afc36c552.png)
 
 Interestingly, there were no precipitation readings for the month of June. This may mean it rains very little during June or
 the people who gather the readings were on vacation catching waves on their surf boards.
 
  ![image](https://user-images.githubusercontent.com/90986041/141600534-c3b2b3dd-325a-4d39-b523-a9a203f017ee.png)
  
## Summary:
  Based on the analyses above, the weather in Oahu appears to be conducive to a year-round Surf 'n' Shake Shop.  The temperatures
  in June and December are comparable with minimum fluctuation.  Further analysis of the precipitation patterns is recommended
  before making a final "go/no-go" investment decision.
  
___
## Resources
_Data Source_: https://github.com/SJLewer/surfs_up/blob/main/hawaii.sqlite

_Python 3.7.6 Script_: https://github.com/SJLewer/surfs_up/blob/main/SurfsUp_Challenge.ipynb

_Analyst_: S. Lewer
