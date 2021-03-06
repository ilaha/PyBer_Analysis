# PyBer_Analysis



## Project Overview


### Analyzing ride sharing data by city type

    - Using pandas and Matplotlib, build a ride-sharing summary Data Frame by city type and create multiple-line graph that demonstrates weekly fares for each city type.









## Resources 

- Data Source: city_data.csv; ride_data.csv

- Software: Python 3.9.4; Pandas Library; Jupyter Notebook; Matplotlip







## Summary


- By merging city data and ride data, we created one whole Pyber data where we could review each unique ride ids, cities, dates, fares per rides, driver count  and city type. 

![Screenshots](https://github.com/ilaha/PyBer_Analysis/blob/main/analysis/Fig1.png)

- When we look at the total rides, fares and drivers for each city type, we it's clear that urban cities hold the highest number.  The average number of rides in the rural cities is about *4* and *3.5* times lower per city than the urban and suburban cities, respectively. 
![Screenshots](https://github.com/ilaha/PyBer_Analysis/blob/main/analysis/Fig6.png)
![Screenshots](https://github.com/ilaha/PyBer_Analysis/blob/main/analysis/Fig7.png)

  - However, if we get the average fare per ride, and average fare per driver for each city type, it's clear that rural city type is about **$11** and **$5** more per ride than the urban and suburban cities *(respectively).
   
  ![Screenshots](https://github.com/ilaha/PyBer_Analysis/blob/main/analysis/Fig3.png)

- When I created a pivot table Data Frame and specified January to April dates, then I was able to create a multi-line graph per these four month to see the fares during this period (_screenshot below_): 

![Screenshots](https://github.com/ilaha/PyBer_Analysis/blob/main/analysis/PyBer_fare_summary.png)


 - I noticed that during this four month period, urban city types actually showing higher fares, followed by suburban city's fares. 
        
        
