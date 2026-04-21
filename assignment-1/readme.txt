Are people more like to conceive during sunnier months than cloudy ones?
No! Not based on this dataset. If anything as the months get sunnier people
are less likely to concieve


I joined the data we were given on the number of sunshine hours per month per city with data from the CDC WONDER
tool. I downloaded the "Births Data Summary - Natality 2016-2024" as counts of births per 1,000 people in the population,
grouped by county of mothers residence and the month. I then assumed we the counties corresponding to each city, aggregating them
such that Seattle was King County, WA, San Francisco was San Francisco County, CA, Chicago was Cook County, IL, Houston was Harris County, TX,
Miami was Miami-Dade County, FL, and New York was New York County, Kings County, Queens County, Bronx County, and Richmond County summed together.
Even though these counties are sometimes an over-approximation for the city, the sunlight encountered in them I assume
will be roughly similar since they are close geographically. I wanted to understand in a certain city when people were most
likely to conceive, not if people conceived more in cities where it was sunnier. So I transformed the births per month to a percentile
of total births per city per month, so if many more people gave birth in one city per capita we could still see how that compared
to other cities by sunniness. I was considering also taking a percentile for sunshine hours but decided to keep it
as a total amount, so that cities with more or less sun overall we could still see what the relative differences where. For birth,
I imputed a conception time by subtracting nine months from the birth time. Then I plotted it as a line chart with different colors for each city,
with the X axis being the sunshine hours of the month, and the Y axis as the percent of conceptions in that city in that month. I was looking to see
if there was an upwards trend as sunshine hours increased per city, did the rate of conceptions also increase?


I choose to keep the city data separate, instead of aggregating as a whole, so I could see if possibly some cities
had different trends than others, since I assume there are many other factors besides sunlight that would influence conception.
Alternatively, I considered doing a heatmap with the same axis instead, which could make sense with more cities, but with
only a few the different lines are still legible. As I said above, I transformed the births into a percentage per month,
in order to remove the factor of overall more births in a city from another when comparing when people had babies. I also
changed the Y axis to not start at zero so we could see the difference better between the terms, since they are all clustered
near 8-9%.

_I wrote this README first and then had codex generate a Vega Lite file to create that visualization as stated here and compile
it using vl2png_
