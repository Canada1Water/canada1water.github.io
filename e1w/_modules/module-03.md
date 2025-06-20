---
title: Digital Elevation Models
---

# Module 3: Digital Elevation Models
**Duration:** 3 hours  
**Instructors:** Eric Kessel, Amanda Taylor

## Learning Objectives

By the end of this module, participants will be able to:
- Distinguish between DSM, DEM, and DTM elevation products
- Select appropriate resolution for modeling applications
- Understand and work with different vertical datums
- Integrate lake bathymetry data with terrestrial elevation models

## Module Content

### Understanding Elevation Model Types

#### Digital Surface Model (DSM)
- Represents the Earth's surface including vegetation, buildings, and other features
- Applications and limitations for hydrological modeling
- Common data sources and characteristics

#### Digital Elevation Model (DEM)
- Represents bare-earth surface
- Processing methods to remove vegetation and structures
- Quality and accuracy considerations

#### Digital Terrain Model (DTM)
- Represents natural terrain features
- Includes natural breaks in slope, ridges, and valleys
- Applications in hydrological flow modeling

### Resolution Considerations
- **Spatial resolution** trade-offs:
  - Computational requirements vs. detail
  - Appropriate resolution for different model scales
  - Impact on flow routing accuracy
- **Vertical resolution** and precision:
  - Accuracy requirements for different applications
  - Error propagation in derived products
- **Data density** and interpolation methods

### Vertical Datums
- Understanding coordinate systems and datums
- **Common vertical datums:**
  - Mean Sea Level (MSL)
  - Ellipsoid heights
  - Geoid models
  - Local and regional datums
- **Datum transformations:**
  - Converting between vertical references
  - Tools and methods for transformation
  - Accuracy considerations

### Lake Bathymetry Integration
- Sources of bathymetric data:
  - Sonar surveys
  - Satellite-derived bathymetry
  - Interpolated depth models
- **Integration techniques:**
  - Merging terrestrial and bathymetric DEMs
  - Handling water surface elevations
  - Ensuring continuity across boundaries
- **Quality control:**
  - Validation methods
  - Identifying and correcting artifacts

### DEM Processing and Conditioning
- **Pre-processing steps:**
  - Pit filling algorithms
  - Noise reduction techniques
  - Edge effects and boundary handling
- **Hydrological conditioning:**
  - Stream burning techniques
  - Enforcing drainage networks
  - Maintaining flow connectivity

## Hands-on Exercises

### Exercise 3.1: DEM Source Comparison
- Download DEMs from multiple sources for the same area
- Compare DSM vs. DEM products
- Analyze differences in resolution and accuracy
- Evaluate suitability for different modeling purposes

### Exercise 3.2: Resolution Analysis
- Work with DEMs at different spatial resolutions
- Analyze impact on derived flow networks
- Assess computational trade-offs
- Develop resolution selection criteria

### Exercise 3.3: Vertical Datum Transformation
- Practice datum transformations using various tools
- Compare results from different transformation methods
- Validate transformations using control points
- Document datum information for model metadata

### Exercise 3.4: Bathymetry Integration
- Integrate lake bathymetry with terrestrial DEM
- Handle water surface elevation consistency
- Create seamless elevation models
- Validate integrated products

## Data Sources
- **Global DEMs:**
  - SRTM (30m, 90m)
  - ASTER GDEM (30m)
  - Copernicus DEM (30m, 90m)
  - ALOS World 3D (30m)
- **High-resolution national/regional:**
  - USGS 3DEP (US)
  - CDED (Canada)
  - Various LiDAR products
- **Bathymetry sources:**
  - GEBCO global bathymetry
  - National hydrographic surveys
  - Research cruise data

## Tools and Software
- **QGIS/ArcGIS** - visualization and analysis
- **GDAL** - format conversion and processing
- **WhiteboxTools** - DEM processing and conditioning
- **Python libraries** - rasterio, elevation, pyproj
- **Datum transformation tools** - PROJ, cs2cs

## Required Reading
- DEM accuracy and quality assessment methods
- Vertical datum fundamentals and transformation procedures
- Best practices for bathymetry integration

## Resources
- DEM data access portals and APIs
- Vertical datum transformation tools and documentation
- Sample bathymetry datasets
- Quality assessment checklists
