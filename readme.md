# Lab 3: Web Map Design

**Assets:**

Within the assets folder, I have uploaded two airports.geojson contains all the airports in the United States. This data is converted from a shapefile, which was downloaded and unzipped from https://catalog.data.gov/dataset/usgs-small-scale-dataset-airports-of-the-united-states-201207-shapefile. For each airport feature, the field CNTL_TWR indicates whether the airport has an air traffic control tower or not. If there is a tower, the value of CNTL_TWR is 'Y', otherwise 'N'. You may need to find an appropriate icon on font awesome. (7 points)

us-states.geojson is a geojson data file containing all the states' boundaries of the United States. This data is acquired from Mike Bostock of D3. The count field indicates the number of airports within the boundary of the state under investigation. So please make a choropleth map based on the number of airports within each state.
