# Surfs_Up

## Overview
We want to start a Surf and Shake shop serving surfboards and ice cream to locals and tourists. Therefore, we created a business plan to acquire investors, like W.Avy, willing to help start this venture. To ensure this business is successful, we gathered data to help our investors make data-driven decisions. For example, W. Avy wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for June and December in Oahu to determine if the surf and ice cream shop business is sustainable year-round. 

## Results
Using Python, Pandas functions and methods, and SQLAlchemy, I filtered the date column of the Measurements table in Hawaii. Next, I used the SQLite database to retrieve all the temperatures for June and December. Then I converted those temperatures to a list, created a DataFrame from the list, and generated the summary statistics.

![june temp](https://user-images.githubusercontent.com/92180070/207151728-2b1b47da-0f25-4806-90ad-3a0991b43970.png)
![Dec Temp](https://user-images.githubusercontent.com/92180070/207151819-feb62f9e-1163-47da-a193-343f55a9df57.png)

### First Major Point: Average Temperature are Similiar
### Second Major Point: Standard Deviation is Small
### Third Major Point: Range in Temperature are Alike

## Summary
To summarize the analysis, temperatures in Oahu are similar in June and December, making this invest stable for investors. There is no need to be concerned about the change of demands due to weather, and every day will be a great day for guests to soak in the sun at our new Surf and Shake shop. If we were to investigate additional data that could affect surfing conditions, it would be atmospheric pressure and wind speed and direction.

### Atmospheric Pressure
The low-pressure system is the most relevant variable regarding the creation of surfing waves. Its air cell, whose pressure is lower than its surroundings, travels across the oceans and seas with the help of the Coriolis force and generates waves as it produces frictional drag on the water surface causing bigger waves or full-blown, powerful storm. Tracking storms and their impact on the coastlines is one of the surfer's most valuable skills. 

### Wind Speed and Direction
The stronger the wind, the more energy is shifted toward the surface of the water; small energy will translate into small waves. So, the speed and direction of the wind are critical to the formation of the first wave trains in the open ocean. The last rule of thumb is that the farther away the wind-water interaction takes place, the better and cleaner the waves. In this case, we get the ground swell, as opposed to the wind swell, i.e., choppy waves created near the coastline.
