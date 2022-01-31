# PyBer_Analysis

## Project Overview
The goal of this analysis was to create a visualization for V.Isualize of a summary dataframe that includes ride-sharing data by city type, specifically using a multiple-line graph showing total weekly fares for each city type. This will, in turn, inform decision-makers at PyBer regarding where they want to take the direction of their business.

1. Analyze student funding.
2. Analyze student test scores. 
3. Aggregate the data and showcase performance trends.
4. Repeat and compare the analysis with Thomas High School 9th grade scores set to null values.

#### Resources used
* Data Source: ride_data.csv, city_data.csv
* Software: Jupyter Notebook (Python, Pandas and Matplotlib library import)

## Results
* What are the differences in ride-sharing data among different city types?
Below we can see the overall comparison of ride-sharing data by city type:

![analysis_summary](https://user-images.githubusercontent.com/87148145/151737360-629f2da4-e168-47d3-8bab-28bca8ff1c8d.PNG)

To start, rural drivers are lacking: they account for approximately 20% of suburban drivers and less than 5% of the amount of drivers found in the urban setting. The reason for this is clear: the more rural the area, the longer the distance for each ride. This fact is also reflected in the average fare per driver, which is significantly higher the more rural the area. 

We can get additional information from the multiple-line chart here:

![Pyber_fare_summary](https://user-images.githubusercontent.com/87148145/151737655-cc3f78dc-abb1-4b52-b945-a94ded6d5fd9.png)

In the four months recorded, total fares were much higher in the urban areas, with suburban and rural, respectively, next in the pecking order. 

## Summary
To summarize, this data may inform future growth opportunities at PyBer. The following points were noted for decision-makers:

1. Since the the total fares in the rural zones are low (about 7% of fare revenue), the company may do well to shift its focus to suburban and urban opportunities. 
2. There are clear spikes in certain dates across the board. Mid- to late February stands out -- perhaps because of Valentine's Day. April 1st appears to be another 'hot zone' for a surge in ride-shares. By calculating fare costs within these date ranges, there may be great potential to increase revenue; conversely, there may be opportunities to bolster rides outside of these suring date ranges. 
3. Finally, I recommend an additional date-specific analysis: instead of looking at a four-month window, we might look at any given range of weekdays vs. weekends, perhaps comparing all 52 weekends in the year. By using this analysis and applying the principles in the second recommendation above, PyBer has yet another opportunity to increase business. 

