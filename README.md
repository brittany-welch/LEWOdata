# LEWOdata
This data was collected May - June 2023 via conducting point counts for Lewis's woodpeckers (Melanerpes lewis) in burned forests located within Deschutes National Forest and White River Wildlife Area in the east Cascades of Oregon. 



Variables
PointID: alphabetical code to identify survey point
PointCode: numerical code to identify survey point
TransectID: the transect in which the points were located
Rep1: replicate one of point count surveys
Rep2: replicate two of point count surveys
Rep3: replicate three of point count surveys
JDR1: Julian date of replicate 1
MinsSinceR1: Minutes since sunrise (the time the survey was started) of replicate 1
JDR2: Julian date of replicate 2
MinsSinceR2: Minutes since sunrise (the time the survey was started) of replicate 2
JDR3: Julian date of replicate 3
MinsSinceR3: Minutes since sunrise (the time the survey was started) of replicate 3
JDR1S: Julian date of replicate 1, centered and scaled for analysis
JDR2S: Julian date of replicate 2, centered and scaled for analysis
JDR3S: Julian date of replicate 3, centered and scaled for analysis
MinScR1: Minutes since sunrise (the time the survey was started) of replicate 1, centered and scaled for analysis
MinsScR2: Minutes since sunrise (the time the survey was started) of replicate 2, centered and scaled for analysis
MinsScR3: Minutes since sunrise (the time the survey was started) of replicate 3, centered and scaled for analysis
ObserverR1: who conducted the survey, replicate 1
ObserverR2: who conducted the survey, replicate 2
ObserverR3: who conducted the survey, replicate 3
WPR1: presence (1) or absence (0) of another woodpecker species at the point during the survey, replicate 1
WPR2: presence (1) or absence (0) of another woodpecker species at the point during the survey, replicate 2
WPR3: presence (1) or absence (0) of another woodpecker species at the point during the survey, replicate 3
WindR1: wind speed based on the Beaufort scale during survey, replicate 1
WindR2: wind speed based on the Beaufort scale during survey, replicate 2
WindR3: wind speed based on the Beaufort scale during survey, replicate 3
Latitude: location of point, latitude
Longitude: location of point, longitude
y_proj: latitude projection
x_proj: longitude projection
FireSev: categorized burn severity at point, derived from the MTBS rDnBR6 raster 
FireName: identifying name of wildfire
FireYear.x: year the fire burned
coh_c2_100: cohesion index of burn severity class 2 at a 100m spatial scale around the point
coh_c3_100: cohesion index of burn severity class 3 at a 100m spatial scale around the point
coh_c4_100: cohesion index of burn severity class 4 at a 100m spatial scale around the point
coh_c2_300: cohesion index of burn severity class 2 at a 300m spatial scale around the point
coh_c3_300: cohesion index of burn severity class 3 at a 300m spatial scale around the point
coh_c4_300: cohesion index of burn severity class 4 at a 300m spatial scale around the point
coh_c2_600: cohesion index of burn severity class 2 at a 600m spatial scale around the point
coh_c3_600: cohesion index of burn severity class 3 at a 600m spatial scale around the point
coh_c4_600: cohesion index of burn severity class 3 at a 600m spatial scale around the point
cnn_c2_100: connectivity index of burn severity class 2 at 100m spatial scale around the point
cnn_c3_100: connectivity index of burn severity class 3 at 100m spatial scale around the point
cnn_c4_100: connectivity index of burn severity class 4 at 100m spatial scale around the point
cnn_c2_300: connectivity index of burn severity class 2 at 300m spatial scale around the point
cnn_c3_300: connectivity index of burn severity class 3 at 300m spatial scale around the point
cnn_c4_300: connectivity index of burn severity class 4 at 300m spatial scale around the point
cnn_c2_600: connectivity index of burn severity class 2 at 600m spatial scale around the point
cnn_c3_600: connectivity index of burn severity class 3 at 600m spatial scale around the point
cnn_c4_600: connectivity index of burn severity class 4 at 600m spatial scale around the point
ctg_c2_100: contiguity index of burn severity class 2 at 100m spatial scale around the point
ctg_c3_100: contiguity index of burn severity class 3 at 100m spatial scale around the point
ctg_c4_100: contiguity index of burn severity class 4 at 100m spatial scale around the point
ctg_c2_300: contiguity index of burn severity class 2 at 300m spatial scale around the point
ctg_c3_300: contiguity index of burn severity class 3 at 300m spatial scale around the point
ctg_c4_300: contiguity index of burn severity class 4 at 300m spatial scale around the point
ctg_c2_600: contiguity index of burn severity class 2 at 600m spatial scale around the point
ctg_c3_600: contiguity index of burn severity class 3 at 600m spatial scale around the point
ctg_c4_600: contiguity index of burn severity class 4 at 600m spatial scale around the point
FireSevMW100: burn severity moving window analysis at 100m spatial scale around the point
FireSevMW300: burn severity moving window analysis at 300m spatial scale around the point
FireSevMW600: burn severity moving window analysis at 600m spatial scale around the point
FireYear.y: the year the fire burned catagorized into 4 groups: 0 = no burn, 1 = recent burn (within the last 6 years of survey window), 2 = intermediate burn (within the last 11 years of survey window), old burn (within the last 20 years of survey window)
avgLive: average live canopy cover present
avgDead: average dead canopy cover
avgTotal: average total canopy cover
totalLiveSn: total number of live trees (>23cm DBH) present
totalLiveDen: live tree density 
totalDeadSn: total number of snags (>23 cm DBH) 
totalDeadDen: snag density
totalTrees: total number of trees (live and dead)
totaltreeDensity: density of trees (live and dead)
avgLiveDBH: average size (DBH) of live trees
avgDeadDBH: average size (DBH) of snags
avgDC: average decay class
Property: 1 = Deschutes National Forest, 2 = White River Wildlife Area
Elev: meters above sea level
