# Vancouver Parks and Green Spaces
GEOS 472 – Exploratory Lab 1: Web Cartography

## Project Overview
This project explores the spatial distribution of public parks and green spaces in Vancouver, British Columbia. Using Maputnik and MapLibre GL JS, the map aims to represent park characteristics within a meaningful urban context.

## Data Source
- **Dataset:** Parks – Polygon Representation
- **Publisher:** City of Vancouver Open Data Portal
- **Records:** 254
- **Format:** GeoJSON
- **Licence:** Open Government Licence – Vancouver
- **Source:** https://opendata.vancouver.ca/explore/dataset/parks-polygon-representation/

## Interactive Map
**Live interactive map:** https://janicepcy.github.io/Exploratory-lab-1/

The map was designed using Maputnik and published through GitHub Pages using MapLibre GL JS. Users can zoom and pan to explore Vancouver's parks, with park labels becoming visible at larger map scales.

## Cartographic Design and Reflection
I chose to map Vancouver's public parks using polygon data to explore how green spaces are distributed across the city. Rather than displaying every park with the same symbol, I classified parks by area and used three shades of green to distinguish smaller parks from larger ones. This helps emphasize differences in park size while maintaining a consistent colour scheme. I also modified the original Positron basemap by changing the water colour to a muted blue and adjusting the appearance of transportation and building layers. These changes were intended to make the parks more prominent without removing the surrounding urban context.

Another important consideration was how the map would appear at different zoom levels. At smaller scales, I prioritized showing the overall distribution of parks rather than displaying too many labels. At zoom levels 13–14, labels are restricted to parks of at least five hectares, while smaller parks can also be labelled from zoom level 15 onward. I encountered difficulties configuring the label layer in Maputnik, particularly with expression syntax and layer ordering. Through testing and adjustments, I was able to display park names above the polygons. One limitation is that labels can still become crowded in areas containing several parks close together, showing the challenge of balancing detail and readability in interactive maps.

## Peer Critique and Acknowledgements
To be completed after the critique session, including disclosure of any generative AI assistance.
