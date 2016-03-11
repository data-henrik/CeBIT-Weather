# CeBIT-Weather
Project featuring a Jupyter Notebook, dashDB and Apache Spark on Bluemix and open data around the CeBIT fair - this is the source for my blog entry at http://blog.4loeser.net/2016/03/coincidence-cebit-visitors-and-weather.html.

The historic weather data for the CeBIT town Hanover, Germany, was obtained from the [Deutscher Wetterdienst](http://www.dwd.de). It can be found on their FTP site: ftp://ftp-cdc.dwd.de/pub/CDC/observations_germany/climate/daily/kl/historical/

The data on previous CeBIT dates was obtained from [Wikipedia](https://de.wikipedia.org/wiki/CeBIT) entry.

Right now the comments in the source of the Jupyter notebook is the only description available for the computing cells. They demonstrate how to connect to dashDB/DB2 from the notebook, fetch data into data frames and use these data frames as input for graphs. While the input data (CeBIT dates and attendees, weather for Hanover) is valid, the goal to find some correlation between the weather conditions and attendance for a computer fair are obviously bogus...
