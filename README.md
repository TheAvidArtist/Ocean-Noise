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



What is the effect of wind and rain on underwater noise? Explain any behavior you observe in your result.
Which one has the highest impact? Rain or wind?
What are the main reasons for observing different spectral levels in Oregon shelf compared to Oregon offshore?

## Part 2: Airgun, Marine Mammals, Earthquake/Volcano Noise


![Fig 9](https://github.com/TheAvidArtist/Ocean-Noise/blob/master/AirgunSpectogram.png)

![Fig 10](https://github.com/TheAvidArtist/Ocean-Noise/blob/master/MammalCallSpectogram.png)

![Fig 11](https://github.com/TheAvidArtist/Ocean-Noise/blob/master/EarthquakeSpectogram.png)


Find a short time period that there is a marine mammal vocalization in recorded data and plot its spectrogram.
Find a short time period that there is an airgun noisein recorded data and plot its spectrogram. 
Find a short time period that there is an earthquake or a volcano eruptionin recorded data and plot its spectrogram.
Compare the bandwidth of these three signals. Are they consistent with what is shown in the Wenz curve(refer to the Ocean Noise slides)?

