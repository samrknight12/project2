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

Clicking on a cluster or manually zooming in will provide more identifiable areas as clusters or individual points.

![Cluster 3](Project2cluster3.png)

In some scenarios, one location may have multiple building permits.

![Cluster 4](Project2cluster4.png)

If a multiple permit location is clicked the points will expand, allowing for easily vision and selection for the user.

![Cluster 5](Project2cluster5.png)

Finally, information such as the permits: 

Issue Date, 
Working Class Group, 
Contractor Name,
Community Name,
and Original Address

Will appear for each point when clicked as a popup menu.

![Cluster 6](Project2cluster6.png)
