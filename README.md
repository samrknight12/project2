# Project2 Leaflet.js Building Permit Map
A web application that uses leaflet.js API and the City of Calgary API to map building permits in Calgary AB based on the permit issue date.

## The Map & Search
When a User is enters the site they are brought to a map centered at Calgary's City Centre. Above the map is a a date search widget where a user can select two dates. These dates can be the same or different and this will search the City of Calgary's API for building permits whose issue dates are within that date range. 

![EnterPage](Project2enterpage.png)

## The Output
There may sometimes be a high number of data points on the map, making it look cluttered. To fix this, high density point areas are clustered at certain zoom levels.

![Cluster 1](Project2cluster1.png)

The extent of the points within these clusters can be seen by the user if they place their cursor over the point.

![Cluster 2](Project2cluster2.png)
