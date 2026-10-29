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

The map was created using Maputnik and MapLibre GL JS and is hosted through GitHub Pages.

## Map Preview
<img width="1440" height="819" alt="Screenshot 2026-10-28 at 9 24 54 PM" src="https://github.com/user-attachments/assets/e3b338ab-73cf-49ca-aea7-f72e334c6110" />

## Cartographic Design and Reflection
This map was designed for readers interested in exploring the distribution and size of public parks across Vancouver. Using the City of Vancouver's Parks – Polygon Representation dataset, I classified park polygons into three area categories: small (under 1 hectare), medium (1–5 hectares), and large (5 hectares or more). A sequential green colour scheme distinguishes the categories, with darker shades representing larger parks. This allows readers to compare park sizes across the city and identify patterns that might be less apparent when all parks are displayed using the same colour. The map focuses on park area rather than park accessibility or quality, so the distribution should not be interpreted as a direct measure of equitable access to green space.

I modified the OpenFreeMap Positron basemap in Maputnik to provide geographic context without overwhelming the park polygons. Roads and buildings were retained in subdued colours to show how parks are situated within Vancouver's built environment, while waterways were styled in muted blue to emphasize the city's coastal geography. I also hid the original basemap park layer and selected land-use and land-cover layers to reduce unnecessary information and avoid confusing background features with the thematic data. These choices apply the cartographic principles of figure–ground contrast and selective omission. Rather than treating the basemap as a fixed background, I considered which features could help readers interpret the relationship between parks and their surrounding urban landscape.

The map was also designed for exploration at multiple zoom levels. At a city-wide scale, readers can compare the overall distribution of differently sized parks, while zooming in reveals more detailed street and building patterns. Park labels were configured to prioritize larger parks at intermediate zoom levels and display more names at closer scales, reducing label congestion. One limitation is that park area alone cannot explain how frequently parks are used or whether residents have equal access to them. Future improvements could incorporate population distribution, neighbourhood boundaries, or pedestrian accessibility data to provide a more detailed understanding of Vancouver's public green spaces.
