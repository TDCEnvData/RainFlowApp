
# TDC Rainfall and River Flow HTML Report

This repository contains a self-contained, styled HTML report displaying rainfall and river flow data across catchments in the Nelson/Tasman region. The report is designed for internal use only by Tasman District Council (TDC) and presents 15-minute and hourly rainfall data, flow measurements, and forecast rainfall (if available) in a tabulated format.

## Overview

The HTML report is automatically generated using R and styled with embedded CSS. It includes:

- **15-Minute Rainfall Table**  
- **1-Hour Rainfall Table**  
- **Rainfall Forecast Table** 
- **River Flow Table** with color-coded return periods  
- **Flow Legend** describing recurrence intervals  

Tables are grouped by region and catchment, and include dynamic styling to highlight significant values.

## Features

- **Color scaling**: Rainfall values use YlOrRd and flow values use custom return period thresholds.
- **Return period mapping**: Flow data is annotated with recurrence intervals (e.g., MAF to 2, >50 years).
- **Catchment headers**: Automatically inserted and styled.
- **Responsive design**: Works on desktop and mobile.
- **Auto-scroll**: Tables scroll to the rightmost (latest) column on load.
- **Auto-refresh-ready**: JavaScript included to support live-updated versions (requires backend integration).
- **Print-friendly**: Styles included for printing one tab per page.

## Notes & Assumptions

- Data is assumed to be raw and not quality controlled.
- This report is **not interactive beyond tab switching** (no filtering or sorting).

## Disclaimer

> This report is for **internal informational purposes only**. Data has not been validated or quality controlled and should not be used as the sole basis for decision-making. Use with caution and context.

## Contact

For questions, updates, or issues with the report, please contact the TDC Hydrology team at environmentaldatarequests@tasman.govt.nz.
