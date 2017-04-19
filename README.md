# Choropleth-map-Netherlands-Bokeh-Python

## Jupyter notebook showing the use of bokeh (Python) to implement a choropleth map
Making a choropleth map using Bokeh (see http://bokeh.pydata.org/en/latest/docs/gallery/texas.html ) based on GEOJSON isn't as easy as you might like.  
This notebook walks through a full example.
The input data used for filling in the map is average household income on a municipality (gemeente) level.  
This is obtained through CBS's open data protocol and the Python 'cbsodata' module to access this API.  
Other data crunching is done in Pandas.

