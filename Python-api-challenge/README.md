# Python-api-challenge
This is my 6th Repository

Analysis of Weather and Vacation
1.	The first noticeable trend in the dataset of cities is that there seems to be an uneven distribution by hemisphere. Around 60-75% of the cities are located in the northern hemisphere, while the remaining 40-25% are in the southern hemisphere. However, this distribution agrees with the fact that most of the Earth's landmass is in the northern hemisphere, which accounts for approximately 70% of the world's landmass. This explains why there are more cities in the northern hemisphere as cities are primarily built on land. So, the city distribution by hemisphere is relatively uniform when considering the landmass percentage in each hemisphere.

2.	Another interesting observation is that the temperature tends to increase gradually as we move towards latitude line in both the northern and southern hemispheres. The correlation between temperature and latitude is quite strong, with r-squared values of approximately -0.7 and 0.8 for the northern and southern hemispheres, respectively. If we were to separate the data based on the 23-degree latitude line instead of the equator, these correlations would likely increase even further. The 23-degree latitude line represents the points on Earth closest to the sun during the summer in the northern hemisphere, resulting in higher temperatures. Conversely, the -23-degree latitude line would show peak temperatures during the winter in the northern hemisphere and the summer in the southern hemisphere.

3.	Lastly, I noticed a trend in the VacationPy notebook 

a.	Humidity levels appear to be quite high worldwide. This is evident from the abundance of red-colored regions on the heatmap, indicating maximum or near-maximum humidity in the displayed areas. 
b.	humidity values seem to be particularly high and continuous near coasts and large bodies of water, such as rivers or lakes, compared to more inland areas of the continents. This is likely because the air near water bodies contains more evaporated water, preventing the climate from becoming too dry. 
c.	Relative humidity can change with temperature, meaning that air at higher temperatures can hold more water than air at lower temperatures. 
Points to note:
-	need to measure the amount of water saturation in the air based on water mass per unit volume we can gain more insights.
https://www.geeksforgeeks.org/plot-mathematical-expressions-in-python-using-matplotlib/
https://pandas.pydata.org/pandas-docs/stable/user_guide/indexing.html#returning-a-view-versus-a-copy
https://desktop.arcgis.com/en/arcmap/10.3/guide-books/map-projections/about-geographic-coordinate-systems.htm
https://pypi.org/project/citipy/
https://openweathermap.org/api
