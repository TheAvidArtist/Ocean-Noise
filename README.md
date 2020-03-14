# Ocean-Noise

## Introduction

In this project we observe the power spectral density vs frequency of weather in the Pacific Northwest Ocean using data from hydrophones.  From this we should be able to determine the relationship between water, wind, and sound in the ocean. In the second half of the project we observe ocean noise from airguns, marine mammals, and earthquakes, and see if they are consistent with known data.



## Part 1: Wind and Rain Noise

In this section we use PSD vs Frequency graphs in the Oregon Shelf and Oregon Offshore regions and compare the difference in data between windy, rainy, windy and rainy, and neither windy nor rainy times.


Rainy day:

![Fig 1](https://github.com/TheAvidArtist/Ocean-Noise/blob/master/ShelfRainy.png)
![Fig 2](https://github.com/TheAvidArtist/Ocean-Noise/blob/master/OffshoreRainy.png)



Windy day:

![Fig 3](https://github.com/TheAvidArtist/Ocean-Noise/blob/master/ShelfWindy.png)
![Fig 4](https://github.com/TheAvidArtist/Ocean-Noise/blob/master/OffshoreWindy.png)



Stormy day:

![Fig 5](https://github.com/TheAvidArtist/Ocean-Noise/blob/master/ShelfStormy.png)
![Fig 6](https://github.com/TheAvidArtist/Ocean-Noise/blob/master/OffshoreStormy.png)



Dead day:

![Fig 7](https://github.com/TheAvidArtist/Ocean-Noise/blob/master/ShelfDead.png)
![Fig 8](https://github.com/TheAvidArtist/Ocean-Noise/blob/master/OffshoreDead.png)



From these graphs we can make a pretty good estimate of the highs, lows, and averages of the sound energy during each time period:

| Place | Weather | Average | High | Low |
| ----- | ------- | ------- | ---- | --- |
| Oregon Shelf  | Rainy  | ~ 51 PSD | ~ 85 PSD | ~ 0 PSD |
| Oregon Offshore  | Rainy  | ~ 55 PSD | ~ 77 PSD | ~ 15 PSD |
| Oregon Shelf  | Windy  | ~ 45 PSD | ~ 80 PSD | ~ -10 PSD |
| Oregon Offshore  | Windy  | ~ 45 PSD | ~ 85 PSD | ~ 0 PSD |
| Oregon Shelf  | Stormy  | ~ 56 PSD | ~ 88 PSD | ~ 12 PSD |
| Oregon Offshore  | Stormy  | ~ 60 PSD | ~ 83PSD | ~ 1 PSD |
| Oregon Shelf  | Dead  | ~ 42 PSD | ~ 79 PSD | ~ -5 PSD |
| Oregon Offshore  | Dead  | ~ 40 PSD | ~ 82 PSD | ~ -3 PSD |


We can see that the average PSD for stormy weather is the highest by far, and then the average for rainy, windy, and dead in that order.  Based on this data, it seems as though wind and rain both have an effect on ocean noise with rain having the higher impact.  Stormy weather also hits the highest values most consistently with rain being the next highest, and then windy and dead weather coming in last.  These 'high' values coincide with the average values in the theory of rain having the highest impact on underwater noise and wind also having an impact, though less so.

It is beneficial to compare the two different locations because they are around the same general coordinates but they have different depths in the ocean (approximately 80m vs 580m deep) and we can see the difference in sound from rain and wind in shallow water vs deep water.



## Part 2: Airgun, Marine Mammals, Earthquake/Volcano Noise


![Fig 9](https://github.com/TheAvidArtist/Ocean-Noise/blob/master/AirgunSpectogram.png)

![Fig 10](https://github.com/TheAvidArtist/Ocean-Noise/blob/master/MammalCallSpectogram.png)

![Fig 11](https://github.com/TheAvidArtist/Ocean-Noise/blob/master/EarthquakeSpectogram.png)


We can see in the Airgun spectogram that the frequency goes up to about 5000 Hz, whereas the Earthquake only reaches about 100 Hz.  The marine mammal vocalization has several different groupings of frequencies between 1000 and 5000 Hz, which makes sense as different marine mammals have different calls at varying frequencies. This matches what is shown in the Wentz curve, as the seismic activity should be under Hz, bubbles can reach between 1000 and 10,000Hz, and general traffic is between and Hz.

![Fig 12](https://github.com/TheAvidArtist/Ocean-Noise/blob/master/WentzCurve.PNG)


## References


Ocean Observatories Initiative. 2020. HYDBB. [online] Available at: https://oceanobservatories.org/instrument-class/hydbb/ [Accessed 13 March 2020].

Ocean Observatories Initiative. 2020. HYDBBA. [online] Available at: https://oceanobservatories.org/instrument-series/hydbba/ [Accessed 13 March 2020].

Project 2. 2020. TheAvidArtist. [online] Available at: https://github.com/TheAvidArtist/MeteorologyPackageProject

Earthquake.usgs.gov. 2020. M 3.9 - 43Km W Of Waldport, Oregon. [online] Available at: https://earthquake.usgs.gov/earthquakes/eventpage/us10008hwk/executive [Accessed 13 March 2020].
