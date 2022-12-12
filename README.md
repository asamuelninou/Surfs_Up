# Surfs_Up

## Overview
We want to start a Surf and Shake shop serving surfboards and ice cream to locals and tourists. We created a business plan to aquire investors, like W.Avy, who is willing to help get this venture started. To ensure this business is successful we gathered data to help our investors make data-driven decisions. W. Avy wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round. We created two technical analysises that sumarizes the temperature for June and December that determines 

## Results
Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in the hawaii.sqlite database to retrieve all the temperatures for the month of June and December. Then I converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics.

![june temp](https://user-images.githubusercontent.com/92180070/207151728-2b1b47da-0f25-4806-90ad-3a0991b43970.png)
![Dec Temp](https://user-images.githubusercontent.com/92180070/207151819-feb62f9e-1163-47da-a193-343f55a9df57.png)

### First Major Point: AverAGE Temperature similiar
### Second Maor Point: Standard deviation is small
### Third Major Point: Range in temperature is similar
## Summary
To summarize the analysis, temperatures in Oahu are similar and the stability in the weather all year round makes investing in this venture stable. There is no need to be concerned in the change of demands due to weather and everyday will be a great day to soak in the sun with at our new Surf and Shake shop. If we were to investigate further conditions that could effect surfing conditons it would be the following: 
### Atmospheric Pressure
The low-pressure system is the most relevant variable regarding the creation of surfing waves. Its air cell, whose pressure is lower than its surroundings, travels across the oceans and seas with the help of the Coriolis force and generates waves as it produces frictional drag on the water surface. "The deeper the depression, the faster this air moves. The faster it moves, the more it drags on the water, and the bigger the waves will be," stress Butt and Russell. These mid-latitude depressions are by far the most relevant sources of waves for surfing. They can quickly develop from a small atmospheric disturbance into a full-blown, powerful storm. Tracking storms and their impact on the coastlines is one of the surfer's most valuable skills, as it could interfere with planning future sessions.

### Wind Speed and Direction
The wind is the beginning - and sometimes the end - of surfing. Waves are energy in motion. But where does this energy come from? "If we're looking from space, it appears as if someone dropped a rock in the ocean, and ripples traveled out from its initial splash," adds Nathan Todd Cool, author of "The WetSand WaveCast Guide to Surf Forecasting." So, the energy from the wind out at sea is transferred into the ocean water and then transformed into wave energy. This newly-created wave energy will travel in the direction the wind is blowing. And obviously, the stronger the wind, the more energy is shifted toward the surface of the water; small energy will translate into small waves. So, as we can see, the speed and direction of the wind are critical to the formation of the first wave trains in the open ocean. The last rule of thumb is that the farther away the wind-water interaction takes place, the better and cleaner the waves. In this case, we get the ground swell, as opposed to the wind swell, i.e., choppy waves created near the coastline.
