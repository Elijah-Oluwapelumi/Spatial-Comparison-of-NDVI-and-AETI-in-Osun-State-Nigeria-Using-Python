 # Spatial Comparison of NDVI and AETI in Osun State, Nigeria, Using Python

## Project Overview

This project examines the spatial distribution of vegetation greenness and Actual Evapotranspiration and Interception (AETI) across **Osun State, Southwestern Nigeria**, during 2025.

The analysis combines Sentinel-2-derived Normalized Difference Vegetation Index (NDVI) with WaPOR Level 1 AETI data to explore how vegetation conditions and actual evapotranspiration vary spatially across the state.

## Study Area

**Osun State, Southwestern Nigeria**

Osun State was selected to examine the spatial variations in vegetation conditions and water consumption through evapotranspiration across the study area during 2025.

## Data Sources

| Data | Source | Purpose |
|---|---|---|
| Sentinel-2 Satellite Imagery | Google Earth Engine | NDVI generation for 2025 |
| WaPOR Level 1 AETI | FAO WaPOR Platform | Actual evapotranspiration and interception assessment |
| Osun State Boundary | Administrative Boundary Dataset | Definition of study area |

## Tools and Technologies

- Python
- Sentinel-2
- FAO WaPOR Level 1
- NDVI
- Raster Processing
- Geospatial Analysis
- Spatial Visualization

## Methodology

### 1. NDVI Generation

Sentinel-2 satellite imagery was used to derive the Normalized Difference Vegetation Index (NDVI) for 2025 to represent vegetation greenness across Osun State.

### 2. WaPOR AETI Data Processing

Dekadal Actual Evapotranspiration and Interception (AETI) data were obtained from the FAO WaPOR platform. Python was used to download and process the raster datasets for the study area.

### 3. Spatial Comparison

The processed NDVI and AETI datasets were visualized side by side using Python to examine their spatial distribution and identify areas with similar or contrasting patterns.

## Results and Observations

The spatial comparison revealed variations in both vegetation greenness and actual evapotranspiration across Osun State.

- **NDVI:** Relatively greener areas were observed across parts of eastern and southeastern Osun State, while mixed vegetation conditions occurred across parts of the western and central regions.
- **AETI:** Higher values occurred in some eastern and southeastern areas, while lower values were observed across several southern and southwestern locations.

These patterns provide an initial understanding of the spatial variation in vegetation conditions and actual evapotranspiration across the state.

However, further statistical analysis is required to establish the strength and nature of the relationship between NDVI and AETI.

## Conclusion

This project demonstrates the integration of satellite-derived vegetation indices and WaPOR evapotranspiration data for spatial environmental assessment.

By combining NDVI and AETI within a Python-based geospatial workflow, the analysis provides an initial basis for investigating the relationship between vegetation conditions and actual evapotranspiration across Osun State.

## Project Visualization

**Spatial Comparison of NDVI and WaPOR Level 1 AETI across Osun State, Nigeria (2025).**

<!-- Insert your final NDVI and AETI comparison map here -->

![Spatial Comparison of NDVI and AETI in Osun State, Nigeria (2025)](images/ndvi_aeti_osun_2025.png)

*Maps prepared using Python.*
