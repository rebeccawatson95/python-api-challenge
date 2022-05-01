# python-api-challenge
# Rebecca Watson

Starting with the data I was able to pull from the weather csv, there are quite a few graphs that can be explained. First, Latitude vs. temperature looks like there is a coorelation between how close to the equator you get and temperature. Something interesting though is that the highest temperatures are around a latitude of 20. When looking at latitude vs humidity, it appears there is little to no coorelation. The same goes for latitude vs. cloudiness and latitude vs wind speed. 

Looking at the linear regression graphs, there is a lot more we can use to predict trends. When the maximum temperature was ploted against latitude, for both the northern and southern hemispheres, the r-values are close to or above 0.5. The r-values are 0.77 and 0.46, respectively. These higher r-values indicate a strong coorelation between latitude and maximum temperature. 

As predicted by the original graphs, the other tests we ran have low r-values, indicating a weak coorelation. This includes latitude vs. humidity, cloudiness, and wind speed which all have r-values of less than 0.05.