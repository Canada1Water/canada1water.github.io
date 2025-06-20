---
title: Watershed Delineation and Model Boundary
---

# Module 2: Watershed Delineation and Model Boundary
**Duration:** 3 hours  
**Instructors:** Eric Kessel, Amanda Taylor

## Learning Objectives

By the end of this module, participants will be able to:
- Determine appropriate model boundaries for HGS applications
- Use drainage basin generation tools effectively
- Apply Whiteboxtools for hydrological analysis
- Understand the relationship between watershed boundaries and model domains

## Module Content

### Determining Model Shape and Boundaries
- Conceptual considerations for model domain selection
- Balancing computational efficiency with model accuracy
- Boundary condition implications
- Scale considerations in watershed delineation

### Drainage Basin Generation Tools
- **HydroSheds** database and applications
- Automated watershed delineation methods
- Flow direction and accumulation algorithms
- Outlet point selection and validation

### Introduction to Whiteboxtools Hydrological Analysis
- Overview of Whiteboxtools capabilities
- Installation and setup
- Key hydrological analysis functions:
  - Flow direction calculation
  - Flow accumulation
  - Stream network extraction
  - Watershed delineation
  - Pit filling and conditioning

### Practical Workflow Development
- Step-by-step watershed delineation process
- Quality control and validation methods
- Integration with HGS model requirements
- Handling complex topography and flat areas

### Boundary Condition Considerations
- Open vs. closed boundaries
- Groundwater flow boundaries
- Surface water boundaries
- Atmospheric boundaries

## Hands-on Exercises

### Exercise 2.1: Basic Watershed Delineation
- Download and prepare DEM data
- Use HydroSheds for preliminary basin identification
- Validate results against known watershed boundaries

### Exercise 2.2: Whiteboxtools Workshop
- Install and configure Whiteboxtools
- Process DEM for hydrological modeling
- Generate flow direction and accumulation grids
- Extract stream networks and watersheds

### Exercise 2.3: Model Boundary Design
- Design model boundaries for a case study area
- Consider different boundary condition scenarios
- Evaluate trade-offs between domain size and computational cost

## Tools and Software
- **Whiteboxtools** - primary hydrological analysis toolkit
- **QGIS/ArcGIS** - visualization and additional processing
- **HydroSheds** - global watershed data
- **Python libraries** - rasterio, geopandas for automation

## Required Reading
- Whiteboxtools user manual (selected sections)
- HydroSheds documentation and data access
- Best practices for watershed delineation in groundwater modeling

## Resources
- Whiteboxtools installation guide
- HydroSheds data download portal
- Sample DEM datasets for practice
- Validation watershed boundaries for comparison
