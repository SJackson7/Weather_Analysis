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
This second chart shows city location by coordinates and maximum temperature. 
![LOCvTEMP](https://user-images.githubusercontent.com/104914008/181100327-b64bb5ff-ac39-4fa9-a66b-14f01c952a0c.png)

#### Humidity (%) versus Latitude and Location
Plotting humidity by overall city latitude (first chart) did not necessarily indicate any strong pattern or correlation. Viewing the second chart by city coordinates, it would appear that the majority of the more humid locations occur near bodies of water, specifically cities near coastlines. When viewing humidity values for both the northen and souther hemispheres (charts three and four) have a slight to very slight correlation between humidy and latitude. Northern hemisphere locations trended to become more humid as latitude increased (correlation of 0.0982, very slight). Souther hemisphere locations became trended less humid (inverse of the northern locations) as latitude approached the equator (correlation of -0.2998, slight). I would expect these values to shift if a different set of cities were examined. The bottom-line here is that there, again, is no strong coorelation between humidity and latitude.

##### Chart 1
This first chart shows latittude versus humidity.
![LATvHUM](https://user-images.githubusercontent.com/104914008/181101809-27c94753-fd3e-46e9-9c27-1db2f489c3ed.png)

##### Chart 2
This second chart shows city location by coordinates and humidity.
![LOCvHUM](https://user-images.githubusercontent.com/104914008/181101753-4f184f18-f874-49d3-9936-8130a5c99491.png)

##### Chart 3
This third chart shows northern latittudes versus humidity.
![LATvTEMP_northern](https://user-images.githubusercontent.com/104914008/181101772-b23f2df6-7162-4e77-9b64-026df3935506.png)

##### Chart 4
This third chart shows southern latittudes versus humidity.
![LATvTEMP_southern](https://user-images.githubusercontent.com/104914008/181101767-47edeb04-3aff-46ed-912d-85135fcfdf8a.png)

#### Cloud Cover (%) versus Latitude and Location
As was the case for humidity, plotting overall city latitude did not indicate a strong pattern or coorelation for cloud cover. While the coorelation values for the southern hemisphere between cloud cover by latitude was higher than humidity (0.3729, slight-moderate) and the northern hemisphere was also higher (0.411, slight-moderate), these values would most likely change if new locations are selected. What is interesting though is while the cloud cover by overall latitude shows clusters of 80-100% cloud cover and 0-20% cloud cover and fair dispersal between 20-80%, it is not until looking at cloud cover by city coordinates that an almost identical pattern occurs along the coastlines much like humidity. This could indicate weather patterns tend to be more unstable along ocean locations.

##### Chart 1
This first chart shows latittude versus cloud cover.
![LATvCLD](https://user-images.githubusercontent.com/104914008/181103558-b0b78ede-5b23-4768-b4bd-53db9e5d5ae6.png)

##### Chart 2
This second chart shows city location by coordinates and cloud cover.
![LOCvCLD](https://user-images.githubusercontent.com/104914008/181103590-e1611cf7-da62-434f-b6f7-6f29f3349fe0.png)

##### Chart 3
This third chart shows northern latittudes versus cloud cover.
![LATvCLD_northern](https://user-images.githubusercontent.com/104914008/181103568-bdd2df4a-4973-4e72-830e-6fa2cc59654b.png)

##### Chart 4
This third chart shows southern latittudes versus cloud cover.
![LATvCLD_southern](https://user-images.githubusercontent.com/104914008/181103573-ab5b03f0-115c-4864-911c-5d1fb9159dc6.png)

All other chart images not shown above are saved to this repository in the 'images' folder.  

<b>Files included</b>
* city_weather_csv for city weather data
* all chart images referenced
* heatmap of humity by location via Google Maps APIs
* hotels in ideal weather locations via Google Maps APIs
