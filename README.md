# LEWOdata

## Project Overview

This repository contains data collected during May–June 2023 through point-count surveys of Lewis's Woodpeckers (*Melanerpes lewis*) in burned forests within the Deschutes National Forest and White River Wildlife Area in the eastern Cascades of Oregon.

The dataset includes point-count survey information, observer and environmental covariates, wildfire characteristics, landscape pattern metrics, and forest structure measurements. These data were collected to investigate relationships between post-fire habitat characteristics, landscape structure, and Lewis's Woodpecker occurrence.

## Data Dictionary

The following table describes the variables included in the dataset, organized by category.

### 1. Survey Information

| Variable | Description |
|---|---|
| `PointID` | Alphabetical code identifying the survey point |
| `PointCode` | Numerical code identifying the survey point |
| `TransectID` | Transect on which the survey point was located |
| `Rep1` | First replicate of the point-count survey |
| `Rep2` | Second replicate of the point-count survey |
| `Rep3` | Third replicate of the point-count survey |
| `ObserverR1` | Observer conducting replicate 1 |
| `ObserverR2` | Observer conducting replicate 2 |
| `ObserverR3` | Observer conducting replicate 3 |

### 2. Survey Timing

Julian dates and minutes since sunrise were recorded for each survey replicate. Scaled variables were centered and standardized for use in statistical analyses.

| Variable | Description |
|---|---|
| `JDR1` | Julian date of replicate 1 |
| `JDR2` | Julian date of replicate 2 |
| `JDR3` | Julian date of replicate 3 |
| `MinsSinceR1` | Minutes since sunrise when replicate 1 began |
| `MinsSinceR2` | Minutes since sunrise when replicate 2 began |
| `MinsSinceR3` | Minutes since sunrise when replicate 3 began |
| `JDR1S` | Julian date of replicate 1, centered and scaled for analysis |
| `JDR2S` | Julian date of replicate 2, centered and scaled for analysis |
| `JDR3S` | Julian date of replicate 3, centered and scaled for analysis |
| `MinScR1` | Minutes since sunrise for replicate 1, centered and scaled for analysis |
| `MinsScR2` | Minutes since sunrise for replicate 2, centered and scaled for analysis |
| `MinsScR3` | Minutes since sunrise for replicate 3, centered and scaled for analysis |

### 3. Survey Conditions and Detection Covariates

| Variable | Description |
|---|---|
| `WPR1` | Presence (1) or absence (0) of another woodpecker species during replicate 1 |
| `WPR2` | Presence (1) or absence (0) of another woodpecker species during replicate 2 |
| `WPR3` | Presence (1) or absence (0) of another woodpecker species during replicate 3 |
| `WindR1` | Wind speed during replicate 1, measured using the Beaufort scale |
| `WindR2` | Wind speed during replicate 2, measured using the Beaufort scale |
| `WindR3` | Wind speed during replicate 3, measured using the Beaufort scale |

### 4. Geographic Information

| Variable | Description |
|---|---|
| `Latitude` | Latitude of the survey point |
| `Longitude` | Longitude of the survey point |
| `y_proj` | Projected latitude coordinate |
| `x_proj` | Projected longitude coordinate |
| `Elev` | Elevation in meters above sea level |
| `Property` | Survey location: 1 = Deschutes National Forest; 2 = White River Wildlife Area |

### 5. Fire History and Burn Severity

| Variable | Description |
|---|---|
| `FireSev` | Categorized burn severity at the survey point, derived from the MTBS relative differenced Normalized Burn Ratio (RdNBR6) raster |
| `FireName` | Name identifying the wildfire |
| `FireYear.x` | Year the wildfire occurred |
| `FireYear.y` | Fire year categorized into four groups: 0 = no burn; 1 = recent burn (within 6 years of the survey window); 2 = intermediate burn (within 11 years of the survey window); 3 = old burn (within 20 years of the survey window) |
| `FireSevMW100` | Burn severity moving-window analysis at a 100 m spatial scale around the survey point |
| `FireSevMW300` | Burn severity moving-window analysis at a 300 m spatial scale around the survey point |
| `FireSevMW600` | Burn severity moving-window analysis at a 600 m spatial scale around the survey point |

### 6. Landscape Pattern Metrics

Landscape metrics describe the spatial configuration of burn severity classes surrounding each survey point. Metrics were calculated at three spatial scales: 100 m, 300 m, and 600 m.

**Cohesion Index (`coh`)**

| Variable | Description |
|---|---|
| `coh_c2_100` | Cohesion index of burn severity class 2 at 100 m |
| `coh_c3_100` | Cohesion index of burn severity class 3 at 100 m |
| `coh_c4_100` | Cohesion index of burn severity class 4 at 100 m |
| `coh_c2_300` | Cohesion index of burn severity class 2 at 300 m |
| `coh_c3_300` | Cohesion index of burn severity class 3 at 300 m |
| `coh_c4_300` | Cohesion index of burn severity class 4 at 300 m |
| `coh_c2_600` | Cohesion index of burn severity class 2 at 600 m |
| `coh_c3_600` | Cohesion index of burn severity class 3 at 600 m |
| `coh_c4_600` | Cohesion index of burn severity class 4 at 600 m |

**Connectivity Index (`cnn`)**

| Variable | Description |
|---|---|
| `cnn_c2_100` | Connectivity index of burn severity class 2 at 100 m |
| `cnn_c3_100` | Connectivity index of burn severity class 3 at 100 m |
| `cnn_c4_100` | Connectivity index of burn severity class 4 at 100 m |
| `cnn_c2_300` | Connectivity index of burn severity class 2 at 300 m |
| `cnn_c3_300` | Connectivity index of burn severity class 3 at 300 m |
| `cnn_c4_300` | Connectivity index of burn severity class 4 at 300 m |
| `cnn_c2_600` | Connectivity index of burn severity class 2 at 600 m |
| `cnn_c3_600` | Connectivity index of burn severity class 3 at 600 m |
| `cnn_c4_600` | Connectivity index of burn severity class 4 at 600 m |

**Contiguity Index (`ctg`)**

| Variable | Description |
|---|---|
| `ctg_c2_100` | Contiguity index of burn severity class 2 at 100 m |
| `ctg_c3_100` | Contiguity index of burn severity class 3 at 100 m |
| `ctg_c4_100` | Contiguity index of burn severity class 4 at 100 m |
| `ctg_c2_300` | Contiguity index of burn severity class 2 at 300 m |
| `ctg_c3_300` | Contiguity index of burn severity class 3 at 300 m |
| `ctg_c4_300` | Contiguity index of burn severity class 4 at 300 m |
| `ctg_c2_600` | Contiguity index of burn severity class 2 at 600 m |
| `ctg_c3_600` | Contiguity index of burn severity class 3 at 600 m |
| `ctg_c4_600` | Contiguity index of burn severity class 4 at 600 m |

### 7. Forest Structure

| Variable | Description |
|---|---|
| `avgLive` | Average live canopy cover |
| `avgDead` | Average dead canopy cover |
| `avgTotal` | Average total canopy cover |
| `totalLiveSn` | Total number of live trees greater than 23 cm DBH |
| `totalLiveDen` | Density of live trees |
| `totalDeadSn` | Total number of snags greater than 23 cm DBH |
| `totalDeadDen` | Density of snags |
| `totalTrees` | Total number of live and dead trees |
| `totaltreeDensity` | Density of live and dead trees |
| `avgLiveDBH` | Average diameter at breast height (DBH) of live trees |
| `avgDeadDBH` | Average diameter at breast height (DBH) of snags |
| `avgDC` | Average snag decay class |

---

## Notes

- Spatial scales refer to the radius around each survey point unless otherwise specified.
- DBH = diameter at breast height.
- MTBS = Monitoring Trends in Burn Severity.
- RdNBR = Relative differenced Normalized Burn Ratio.
- The `.x` and `.y` suffixes distinguish separate fire-year variables retained in the dataset.

## Study Locations

- Deschutes National Forest, Oregon
- White River Wildlife Area, Oregon
