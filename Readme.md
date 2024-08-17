# WeatherGami
## Written By Jared Rennie (@jjrennie)

Ever hear of a scorigami? It's an event in sports where a final score has never happened in its history. For example, in the <a href='https://nflscorigami.com/' target="_blank">National Football League</a>, a 20-17 score has happened over 285 times, but a 70-20 score has only happened once. When the Miami Dolphins beat the Denver Broncos 70-20 on September 24th, 2023, that was considered a scorigami!

Well, inspired by this, Jonathan Kahl wrote an <a href='https://journals.ametsoc.org/view/journals/bams/104/10/BAMS-D-23-0035.1.xml' target="_blank">article</a> in the Bulletin of the American Meteorological Society describing the concept of 'WeatherGami', utilizing the days Maximum and Minimum temperature at a given area. Since <a href='https://www.ncei.noaa.gov' target="_blank">NOAA NCEI</a> holds all of the worlds weather data, it makes sense to see how WeatherGami works on their station database. This code does that! 

### What You Need

First off, the entire codebase works in Python 3. In addition to base Python, you will need the following packages installed: 
- requests (to access the api)
- pandas (to slice annd dice the data)
- matplotlib (to plot!)
    
The "easiest" way is to install these is by installing <a href='https://www.anaconda.com' target="_blank">anaconda</a>, and then applying <a href='https://conda-forge.org/' target="_blank">conda-forge</a>. Afterward, then you can install the above packages. 

### Launch right now with binder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/jjrennie/weathergami/HEAD?labpath=weathergami.ipynb)
