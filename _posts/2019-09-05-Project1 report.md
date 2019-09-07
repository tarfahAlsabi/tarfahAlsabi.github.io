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

after cleaning and analyzing the data we get these results for the top ten most crowded stations based on the number of exists

![top ten station by the # of exists]({{ site.url }}/images/Top_Ten_Stations.png)



then we extract the top five and start analyzing them to get the most  crowded day , time and turnstile and graph them to make them easy to understand and read

![the crowded days in the weeks]({{ site.url }}/images/Crowded_days_in_the week.png)

![the crowded time of the day]({{ site.url }}/images/Crowded_time_in_the_week.png)

![top ten turnstilles by the # of exists]({{ site.url }}/images/top_ten_turnstiles.png)



# Conclusion

based on the results we had we recommend the street team to focus on:

-  34-ST_PENN STA, GRD CNTRL, 34- ST HERALED, 14 ST_UNION, and TIMES SW-42 ST station.
- avoid weekend and focus on Wednesday and Thursday.
- be in the stations between 8:00 am  to 11:00 am.



