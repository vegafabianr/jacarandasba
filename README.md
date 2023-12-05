# jacarandasba
This is a map of hexagons depicting the distribution of jacaranda trees in Buenos Aires City.

To create it, I used two tree datasets from the Government of the City of Buenos Aires. These datasets are available at: https://data.buenosaires.gob.ar/dataset/. Both datasets contain information about the city's trees, but the information included in each dataset is different, so I decided to combine them. (It is possible that both datasets may not be very precise.)

The main tool in the code is the hexbin function from matplotlib. Other required libraries include pandas, geopandas, and shapely.

The aesthetic inspiration for this graph comes from the "Cherry Blossoms of Washington DC" map, created in R by Samia Baig, which entered the longlist of Information is Beautiful Awards 2023 (https://github.com/samiaab1990/30-day-map-challenge/blob/main/hexagons/cherry_blossom.png).

![Hexagon map depicting the Jacarandas of Buenos Aires City](https://github.com/vegafabianr/jacarandasba/blob/main/map.png)
