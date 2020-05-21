---
title: 'Nighttime sky quality in the Big Bend'
date: 2020-05-30
permalink: /posts/2020/05/night-sky-quality-BIBE
tags:
  - Big-Bend
  - night-sky
---

![image](https://raw.githubusercontent.com/katyabbott/katyabbott.github.io/master/assets/Screenshot_of_dashboard.png)

As a GIS technician at Big Bend National Park, one of my first projects was to explore and visualize changes in night sky quality in and around the park, using satellite data. On board the Suomi NPP satellite is an instrument with a sensor, the VIIRS Day/Night Band (DNB), that can detect nighttime radiance at 15-arc second resolution. While this data is incredibly useful for detecting and analyzing sources of nighttime light, it's hard to interpret in terms of sky quality -- i.e., how does light from a city nearby affect my stargazing experience? How much ambient anthropogenic light is enough to obscure the Milky Way? 

Expanding upon previous work by the park service to calculate and quantify night sky quality from VIIRS DNB data, I developed an algorithm that uses a Fast Fourier Transform to quickly and efficiently sum the effect of night radiance up to 300 kilometers away, using an equation to accounts for attenuation of light as it travels further from the source. I used this algorithm to analyze more than 5 years of night radiance data in the Big Bend region (going as far back as the VIIRS instrument has been operational) and estimate sky quality classes in the area ranging from good to threatened (where the Milky Way is invisible). You can view the results of this analysis [here](https://nps.maps.arcgis.com/apps/opsdashboard/index.html#/406df2fc55574ea4b4f17af2863d2767) and learn more about the code that went into making this project [here](https://bigbendnp.github.io/nightskyquality/). The code is designed to work for any region, so other parks and citizen scientists can make night sky quality maps for their own landscapes, too.  
