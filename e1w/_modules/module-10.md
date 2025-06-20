---
title: Monitoring Data
---

# Module 10: Monitoring Data
**Duration:** 3 hours  
**Instructors:** Eric Kessel, Amanda Taylor

## Learning Objectives

By the end of this module, participants will be able to:
- Manage time series data and timestamps effectively
- Work with streamflow monitoring datasets
- Process groundwater level measurements
- Compare simulated vs. observed data using statistical metrics
- Apply the HydroGof package for model evaluation

## Module Content

### 10.1 Time Series and Time Stamp Management
- Time series data structures and formats
- Time zone handling and UTC conversions
- Temporal alignment and resampling
- Gap filling and quality control procedures
- Aggregation and statistical summaries

### 10.2 Streamflow Data
- Stream gauge networks and data sources
- Discharge measurement techniques and uncertainties
- Flow duration curves and statistical analysis
- Seasonal patterns and trend analysis
- Integration with model boundary conditions

### 10.3 Groundwater Levels
- Monitoring well networks and data collection
- Water level measurements and corrections
- Hydraulic head calculations
- Spatial interpolation techniques
- Long-term trends and variability

### 10.4 Simulated vs. Observed Comparison
- Model calibration principles
- Objective function selection
- Statistical performance metrics
- Visual comparison techniques
- Uncertainty quantification

### 10.5 HydroGof Package for Model Evaluation
- **Goodness-of-fit statistics:**
  - Nash-Sutcliffe efficiency (NSE)
  - Root mean square error (RMSE)
  - Percent bias (PBIAS)
  - Correlation coefficients
- **Time series analysis tools:**
  - Hydrograph plotting
  - Flow duration curve comparison
  - Seasonal performance assessment

## Practical Exercises

- Processing raw monitoring data
- Creating quality-controlled time series
- Calculating goodness-of-fit statistics
- Generating comparative plots and reports

## Data Sources

- Water Survey of Canada (WSC)
- Provincial groundwater monitoring networks
- USGS water data
- Environmental monitoring databases

## R Packages and Tools

- **hydroGOF:** Goodness-of-fit functions for hydrology
- **dplyr:** Data manipulation and analysis
- **ggplot2:** Advanced plotting and visualization
- **lubridate:** Date and time handling
- **zoo:** Time series object handling

## Key Takeaways

- Quality monitoring data is essential for model calibration and validation
- Proper time series management prevents common modeling errors
- Multiple metrics should be used to evaluate model performance
- Visual inspection complements statistical analysis
- Uncertainty in observations affects model evaluation
