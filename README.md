***Please note: If you are using Dark Mode, the graph texts may not show properly. 

## Weather Analysis and Ideal Vacation Locations

For the weather analysis, 594 cities from around the world were selected where I examined the following relationships to the city's latitude:
* Temperature (°F)
* Humidity (%)
* Cloud Cover (%)
* Wind Speed (mph)

I obtained the weather data from OpenWeatherMap API as of July 26, 2022 at 10:33:33 AM. I've included my observations for each section as well as a CSV file of the pulled city data and chart images for the above relationships by overall latitute, city coordinates (by latitude and longitude), northern hemisphere by latitdue and southern hemisphere by latitude.  

### Observations
#### Maximum Temperature (°F) versus Latitude and Location
Given the data and looking at Latitude versus Temperature, temperature increases as you approach the equator from the south (0° Lat) and continue to increase until about the 20° latitude mark. This makes sense as latitudes between -23.5° and 23.5° are in the Torrid (Tropic) Zone and have generally higher temperatures. You can see this trend not only in the first scatter chart, but also when viewing the second chart which displays city location by coordinates and temperature scale. Also notice that temperatures along western coastline of South America are much cooler in the identified zone due to the Andes Mountain chain.

##### Chart 1
This first chart shows latittude versus maximum temperature with lines indicating the Torrid Zone. 
![LATvTEMP](https://user-images.githubusercontent.com/104914008/181065852-df6c231c-6489-46d3-98d6-5e0197d6d3d0.png)

##### Chart 2
This second chart as referenced shows city location by coordinates and maximum temperature. 
![LOCvTEMP](https://user-images.githubusercontent.com/104914008/181100327-b64bb5ff-ac39-4fa9-a66b-14f01c952a0c.png)

#### Humidity (%) versus Latitude and Location
Plotting humidity by overall city latitude (first chart) did not necessarily indicate any pattern or correlation. Viewing the second chart by city coordinates, it would appear that the majority of the more humid locations occur near bodies of water, specifically cities near coastlines. When viewing humidity values for both the northen and souther hemispheres (charts three and four) have a slight to very slight correlation between humidy and latitude. Northern hemisphere locations trended to become more humid as latitude increased (correlation of 0.0982, very slight). Souther hemisphere locations became trended less humid (inverse of the northern locations) as latitude approached the equator (correlation of -0.2998, slight). I would expect these values to shift if a different set of cities were examined. The bottom-line here is that there, again, is no strong coorelation between humidity and latitude.
