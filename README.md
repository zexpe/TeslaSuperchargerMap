# TeslaSuperchargerMap
A heat map of distances to the nearest Tesla Supercharger (SuC) sites in mainland UK and Ireland (most islands excluded because the routing doesn't consider ferry routes so would be inaccurate).

Site locations are indicated by blue dots and areas in white are within 15 miles of a supercharger. Folkestone Eurotunnel SuC isn't included as it's not useful for travel within the UK.

Code is written in Python, using Matplotlib for plotting, OSMnx to retrieve the OpenSteetMap road data (down to secondary roads level), [taxicab](https://pypi.org/project/Taxicab/) for optimal route-finding. The SuC location data is from https://supercharge.info.
