# METIS Project 1 Post

This is the analysis for WomenTechWomenYes  **(WTWY)**, to help their street teams to gain more signups for the gala that will take place on the begging of summer>

we get the data for the subway from this site [MTA](http://web.mta.info/developers/turnstile.html)



## Our Goals

our goals was to analysis the data we have and extract the following: 

- Top five most crowded station by number of exits 

- The most crowded day.

- The most crowded time.

- The most turnstile.

## How Did We Clean The Data
we start the analysis by cleaning the data by:

- Strip White Spaces.

- Assure there is no NaN values.

- Extract the actual from entries and exits values.

  - Replace the negative values by zero.

  - Set a limit for the entries and exits values.

- Parse Date & Time columns to timestamp.
- searching for the stations near the airports (LAGUARDIA and JFK) and exclude them.

# The Result

[top ten station by the # of exists]({{ site.url }}/images/Top_Ten_Stations.png)



[top ten turnstilles by the # of exists]({{ site.url }}/images/top_ten_turnstiles.png)



[top ten station by the # of exists]({{ site.url }}/images/Top_Ten_Stations.png)



[top ten station by the # of exists]({{ site.url }}/images/Top_Ten_Stations.png)