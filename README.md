# Mission-to-Mars

## Overview
A website was made using the scraping method that we learned through various exercises in the module. This includes information on Mars with images of the four hemispheres and facts of the planet, using BeautifulSoup and Splinter. The information was then stored on a Mongo database. From there we used a web application to display the data and alter the design to accommodate a mobile friendly interface using Bootstrap. The results is a streamlined, functional, and interactive website.  
## Resources/Tools
-Installed Splinter, bs4 to import Beautiful Soup
-imported pandas, datetime
-downloaded chromedriver.exe, ran mongoBD (brew services for Mac)
-run app.py
-opened chrome with localhost:5000 (VS code, terminal)

## Results/sample of website:
![](https://github.com/holleyvoegtle/Mission-to-Mars/blob/main/images/image1.png)

![](https://github.com/holleyvoegtle/Mission-to-Mars/blob/main/images/image2.png)

## Scrape URLs
* [Mars News From NASA]( https://mars.nasa.gov/news/ "Text")
* [Feature Image JPL Nasa]( https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars "Feature-Image")
* [Mars Facts From Space Facts]( http://space-facts.com/mars/ "Table")
* [Mars Weathers From NASA]( https://mars.nasa.gov/insight/weather/ "Text")
* [Mars Hemisphere]( https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars "Images")
