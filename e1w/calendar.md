---
layout: page
title: Modules
description: Course modules and learning materials.
nav_order: 3
---

# Course Modules
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

This course is organized into 10 comprehensive modules, each designed to build your expertise in data management for HydroGeoSphere modeling.

## Module 1: Introduction to HGS and GIS Roles in Modeling
**Duration:** 3 hours | **Instructors:** Guido Vettoretti, Brayden McNeill, Steven Frey

- Introduce the course overall and presenters
- Overview of HGS model structure and requirements
- GIS layers required in HGS (watershed delineation, elevation, land surface, geology, hydrology, climate)
- Common data sources (HydroSheds, WorldCover, SoilGrids, LAI Copernicus, DEMs, geology maps)
- CRS and reprojection basics
- Common data formats (vector vs raster vs gridded timeseries)
- ISO 19115: Geographic information – Metadata
- Data management best practices

## Module 2: Watershed Delineation and Model Boundary
**Duration:** 3 hours | **Instructors:** Eric Kessel, Amanda Taylor

- Determine the shape of your model
- Drainage Basin generation tools (HydroSheds)
- Introduction to Whiteboxtools Hydrological Analysis
- Model boundary considerations and boundary conditions
- Practical watershed delineation workflows

## Module 3: Digital Elevation Models
**Duration:** 3 hours | **Instructors:** Eric Kessel, Amanda Taylor

- DSM/DEM/DTMs - understanding different elevation products
- Resolution considerations and selection criteria
- Vertical datums and coordinate systems
- Lake bathymetry integration
- DEM processing and quality control

## Module 4: Geology Datasets
**Duration:** 3 hours | **Instructors:** Eric Kessel, Amanda Taylor

- Soils – near surface unconsolidated materials
- Surficial geology – unconsolidated materials
- Bedrock geology – consolidated materials
- Depth to bedrock - elevation of consolidated materials
- Material properties assignment and uncertainty

## Module 5: Land Surface and Hydrological Datasets
**Duration:** 3 hours | **Instructors:** Eric Kessel, Amanda Taylor

- Stream delineation and channel properties
- Lakes and Waterbodies characterization
- Land cover and overland flow properties
- Leaf Area Index (LAI) datasets and applications
- Surface-groundwater interaction modeling

## Module 7: Climate Datasets
**Duration:** 3 hours | **Instructor:** Guido Vettoretti

- Precipitation, Snow, and Liquid Water Flux
- Air Temperature processing and quality control
- Potential Evaporation methods:
  - Hogg method (temperature-based)
  - Priestley-Taylor method (energy balance)
  - Penman-Monteith method (combination approach)
- Soil temperature datasets and initialization

## Module 8: Finite Element Mesh
**Duration:** 3 hours | **Instructor:** Amanda Taylor

- What is a FEM for HGS? Fundamentals and requirements
- Open source (GMSH) vs closed software (Algomesh) comparison
- Spline controls and geometric representation
- Polygon properties and material zone definition
- Edge lengths, optimization and Mesh quality assessment
- File formats and export procedures

## Module 9: Automation and Scripting GIS Workflows
**Duration:** 3 hours | **Instructor:** Eric Kessel

- Introduction to Python and R for GIS
  - Python: geopandas, rasterio for spatial data processing
  - R: sf, terra packages for spatial analysis
- Model reproducibility and documentation best practices
- Workflow automation strategies and implementation
- Integration with HGS preprocessing workflows

## Module 10: Case Study Example
**Duration:** 3 hours | **Instructor:** TBD

- Case study: full GIS pipeline to build a new HGS model
- C1w-model-builder.R framework walkthrough
- Run through each pre-assembled module package top to bottom
- Quality control and validation procedures
- Troubleshooting common issues and solutions

## Module 11: Monitoring Data
**Duration:** 3 hours | **Instructors:** Eric Kessel, Amanda Taylor

- Time series and time stamp management
- Streamflow data processing and analysis
- Groundwater level measurements and corrections
- Review and compare simulated vs observed timeseries using HydroGof
- Model calibration and validation techniques

---

{% for module in site.modules %}
{{ module }}
{% endfor %}
