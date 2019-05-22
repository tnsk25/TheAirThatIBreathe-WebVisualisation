Project 3 - The Air that I Breathe - CS 424 Visualization Analytics - Spring'19

Will you need your snow boots tonight? Should you bring an umbrella? Accurate weather predictions 
are important for planning our day-to-day activities. Weather forecasting helps us to make more 
informed daily decisions, and may even help keep us out of danger.
When weather events happen, economic repercussions usually follow. Consumer behavior as well as 
supply and demand for a product or raw material can be affected. Energy demand soars during heatwaves; 
insurance claims rise after hailstorms; snow slows in-store shopping but can increase online sales; 
and grain prices spike during drought. Understanding how those impacts affect the U.S. economy has 
spurred a growing demand for analysis of real-time weather and climate data.
An increasing number of companies are faced with the need to adapt their business models based on 
weather volatility. Weather alone can cause the gross domestic product (GDP) to fluctuate 
3 to 6 percent a year, or as much as $1.3 trillion, based on a National Weather Service analysis. 
Demand for value-added weather services is projected to grow by 10–15 percent a year.
Observations can provide forecasters real-time information that they are able to react to in order 
to accomplish things like issuing life-saving weather warnings, make critical adjustments to aviation 
forecasts, and much, much more. The collection of domestic and international observation systems add up 
to billions of observations of the Earth’s atmosphere measured each day.
As society becomes more sensitive to weather, the importance of instantaneous weather prediction for the 
protection of lives and property and continued economic growth increases. For example, the U.S. population 
that resides within 50 miles of the nation’s coastlines and is most threatened by hurricanes and flooding 
is growing rapidly. Such population growth in these and other high-risk areas significantly increases the 
need for improved weather predictions and warnings to minimize risks to life and property. Another consideration 
is that the new economic concept of “just-in-time manufacturing” uses computer-timed and -directed supply systems 
to eliminate the warehousing of parts and products at ports and factories. However, even minor weather 
disruptions of land, sea, and air-supply-system pathways caused by snow, ice, and high-wind weather systems 
can now have large, leveraged impacts on these production systems, whereas previously they had little effect.
Real-time weather-readings can be used to aid fleets in accident reconstruction and crash-related insurance claims 
as well – expanding the potential return on investment (ROI) for such technology. Farmers need information to help
them plan for the planting and harvesting of their crops. Airlines need to know about local weather conditions 
in order to schedule flights. 
There is a wealth of environmental data used in product and service development as well, for instance:
Energy traders develop consumer-demand forecasts when weather is expected to impact a region.
Insurance companies apply forensic analysis to weather-related accidents and claims.
Transportation providers determine where to build facilities so that fog, snow, or other weather factors 
pose fewer challenges to logistics.
Retailers analyze how seasonal patterns can affect merchandising and operations. 
Here’s another important thing we use the weather for, and it’s not something you’re probably thinking of. 
The weather is often the go-to ice-breaker when you’re meeting someone new and you’re not sure 
what you have in common. We all have the weather in common. 

Controls for choosing parameters to visualise such as Light, Tempreature, Humidity and 
various pollutants have been given as checkboxes to compare amongst any subset of choices. 
The leaflet also provides options to view the map in Mountainous/Light/Street View. 
Further, the user can also choose to view each of the data points in imperial/metric units.


Please follow the below to run the code.

Software required to run the code: R and R Studio

To download and install R: From site https://cran.cnr.berkeley.edu/ and installing it. (R (20178-12-20 Eggshell Igloo))

To download and install R-Studio: From site https://www.rstudio.com/products/rstudio/download/ and installing it. (R-Studio (1.1.463))

Libraries needed to run the application:

library(shiny)
library(shinydashboard)
library(ggplot2)
library(lubridate)
library(DT)
library(grid)
library(leaflet)
library(scales)
library(shinycssloaders)
library(shinyWidgets)
library(tidyverse)
library(tmap)
library(tmaptools)
library(sf)
library(splitstackshape)
library(cdlTools)
library(AotClient)
library(tidyr)
library(darksky)
library(rgdal)
library(sp)
library(spatstat)  # Used for the dirichlet tessellation function
library(maptools)  # Used for conversion from SPDF to ppp
library(raster)    # Used to clip out thiessen polygons
library(httr)
library(jsonlite)
library(rjson)
library(ropenaq)
library(promises)
library(future)
library(plyr)
plan(multiprocess)

To see what libraries are currently installed, in the terminal at the > prompt, type installed.packages()[,1:2]

If any library is missing, install them using install.packages(). Example: install.packages(shiny)

Now to run the application, from the folder, open app.R file in R Studio. Once the file opens, click on "Run App" option on the right top of the file window. This opens the application.
