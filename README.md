“What’s the weather like as we approach the equator?”

See the included Python script which visualizes the weather of 545 cities across the world.  Via citypy and the OpenWeatherMap API, I randomly sampled a set of unique cities based on latitude and longitude, performed a weather check on each of the cities using a series of successive API calls, printed a call log and saved both a CSV of all data retrieved and png images for each scatter plot.

Included are the following scatter plots:

Temperature (F) vs. Latitude
Humidity (%) vs. Latitude
Cloudiness (%) vs. Latitude
Wind Speed (mph) vs. Latitude

Observed Weather Trends:

1.	Generally speaking, the closer one gets to the equator, the hotter it gets.  The same is the case with this analysis; for the most part.  The current trend seems to be a bit hotter in the northern part of the tropics vs. the southern hemi; probably due to the fact that summer is right around the corner in the north.
2.	Once you get inside 20 degrees latitude; it’s either dumping rain or “Dry as the Savanah.”  Compare this to north and south of the tropic lines, where it seems evident that the rates of humidity are more regularly distributed (more so in the northern hemisphere at the time of the call).
3.	At the time of this API call, the extremes of cloudiness seem to be more evident the closer one gets to the equator; either 100% cloudiness or 0% and not much of anything to speak of any significance in between. 
4.	There seems to be more data for cities in the northern hemisphere than in the south…  Is it possible that many of the southern hemi cities are getting skipped due to 404 errors because they don’t meet the citipy min population requirement of 500?
