# surfs_up

## Overview of the analysis: 

Conduct weather analysis for Oahu Island in Hawaii using local precipitation and temperature data in order to determine if the surf and ice cream shop business is sustainable year-round. This will help convince investor W. Avy to invest in Surf n’ Shake shop which would serve surfboards and ice-cream  to locals and tourists.

### Purpose:

The purpose of this analysis is to determine if 

 - Weather trends (precipitation, temperature) in June and December in Oahu, are favourable for surf and ice cream shop to have the business sustainable year-round.
 - The analysis steps are:
    -	 Loading the meteorological data from a SQLite database file.
    - 	Writing queries to examine temperature data collected in the months of June and December.
    - 	Calculating summary statistics (especially min, max, and average temperatures collected).


### Results:

#### June Weather Stats:

![](https://github.com/Sheetaltkr/surfs_up/blob/main/Resources/June_temps.png)

- Minimum temp: 64
- Maximum temp: 85
- Mean temp: 75

The weather in June is great for icecream and surfing as the temperatures are not lower than 64 and not higher than 85.

#### December Weather Stats:

![](https://github.com/Sheetaltkr/surfs_up/blob/main/Resources/Dec_temps.png)

- Minimum temp: 56
- Maximum temp: 83
- Mean temp: 71

The weather in December is good for icecream and surfing as the temperatures are between 56 and 83. However the business may be slightly slower than in June.


### Summary:

- The mean temperatures for June to December in Oahu, Hawaii is 75 and 71 respectively making these months favorable for the icecream and surf shop business sustainable year round.
- The first, second and third quartile values in statistic summary for June and Temp are between 64 and 77, which show good temperature distribution.
- The maximum temperature is not more than 85 and minimum is not less than 56 making it perfect weather for surfing and icecream.

### Additional queries:

To gather more data to determine how favourable the weather is for the surf n shake shop queries given below could be helpful:

- Queries to pull precipitation values in Oahu
- Queries to pull wind speed at Oahu

