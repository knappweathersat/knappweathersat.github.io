---
layout: project
title: GridSat-B1
subtitle: Gridded Satellite (GridSat) B1 data
permalink: /gridsat-b1/
featured_image: /assets/images/GulfCoast.jpg
image_caption: GridSat-B1 global coverage
related_links:
  - title: NOAA GridSat-B1 CDR Page
    url: https://www.ncei.noaa.gov/products/gridded-geostationary-brightness-temperature
  - title: ISCCP B1 Data page
    url: https://www.ncei.noaa.gov/products/satellite/international-satellite-cloud-climatology-b1
  - title: Browse GridSat Imagery
    url: https://www.ncei.noaa.gov/gibbs/  
  - title: Related Publications
    url: /publications/
---

## Overview

GridSat-B1 is one of NOAA's first operational Climate Data Records (CDRs), providing a long-term, consistent record of global infrared brightness temperature observations from geostationary satellites. Developed to support critical climate monitoring and research applications, GridSat has established a reputation as a foundational dataset for understanding long-term climate trends and variability.

As a pioneering climate data record, GridSat merges observations from multiple geostationary satellites spanning several decades, creating a seamless, calibrated dataset that enables researchers and decision-makers to analyze climate patterns and changes over time. The product continues to evolve with modernization efforts to incorporate next-generation satellite capabilities while maintaining scientific continuity with the historical record.

## Data access

### HTTPS bulk access
[Data for 1980-present are available by HTTPS download](https://www.ncei.noaa.gov/data/geostationary-ir-channel-brightness-temperature-gridsat-b1/access/)

### NOAA Open Data Dissemination (NODD) - AWS

The full period of record is available on the cloud:
* Description: Gridsat B1
* Resource type: S3 Bucket
* Amazon Resource Name (ARN):arn:aws:s3:::noaa-cdr-gridsat-b1-pds
* AWS Region: us-east-1
* AWS CLI Access (No AWS account required): aws s3 ls --no-sign-request s3://noaa-cdr-gridsat-b1-pds/
* Explore: [Browse Bucket](https://noaa-cdr-gridsat-b1-pds.s3.amazonaws.com/index.html)

## Presentations and papers
* [GridSat-B1 Poster at the 2026 AMS Annual Meeting](/assets\files\AMS Houston GridSat B1 Poster.pdf)

## Data Description

GridSat-B1 integrates infrared brightness temperature observations from the global constellation of geostationary weather satellites, including:

- **Temporal extent**: Multiple generations of various geostationary platforms: Meteosats 2 - 11, 
GOES 4 - 19, and Himawari 1-8. This data spans decades of data but provide a temporally consistent record.
- **International Partners**: Data from JMA, EUMETSAT and other international geostationary satellite operators
- **Global Coverage**: Near-continuous observations from the full geostationary satellite constellation

The dataset employs sophisticated calibration methodologies to ensure consistency across different satellite platforms and generations:

- **Inter-satellite Calibration**: Advanced procedures using reference datasets including HIRS and VIIRS Global Area Coverage (VGAC) data
- **Matchup Algorithms**: Matching ISCCP B1 with HIRS and VIIRS for next-generation calibration 
- **Quality Assurance**: Comprehensive validation frameworks maintaining data integrity and climate record consistency
- **Long-term Continuity**: Careful assessment procedures to ensure seamless extension of the climate record across satellite transitions

## Applications

GridSat-B1 serves diverse scientific and operational applications:

- **Humanitarian Response**: Critical data source for USAID drought monitoring and early warning systems
- **Climate Research**: Foundational dataset for studying long-term climate trends, variability, and change
- **Weather Pattern Analysis**: Supporting research on tropical systems, convection, and large-scale atmospheric circulation
- **Historical Climate Studies**: Enabling analysis of multi-decadal climate patterns and trends
- **Operational Monitoring**: Providing consistent observations for ongoing climate assessment and reporting

The established quality and long temporal extent make GridSat particularly valuable for applications requiring reliable historical climate information.

## Technical Details

GridSat-B1 employs robust methodologies designed to meet NOAA Climate Data Record standards:

- **Processing Framework**: Operational algorithms following NOAA CDR Program requirements and documentation standards
- **Calibration Approach**: Evolving methodologies incorporating advanced reference datasets for improved accuracy
- **Validation Procedures**: Comprehensive comparison with historical records and reference datasets to ensure climate continuity
- **Quality Control**: Multi-level quality assurance procedures maintaining GridSat's established reputation
- **Modernization**: Ongoing upgrades to integrate next-generation satellite capabilities while preserving data record integrity
- **Automation**: Sustainable operational processing designed for long-term climate data stewardship

The technical implementation emphasizes maintaining scientific integrity while ensuring operational continuity, leveraging decades of experience in satellite climate data production to deliver a reliable, trusted climate data record.
