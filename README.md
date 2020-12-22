install.packages("sf") 
install.packages("tmap")
library(sf) 
library(tmap)
#now importing shapefile
London_map <- read_sf ("InnerLondon_ward_polygons.shp")
#quick map
qtm(London_map) 
