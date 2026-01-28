---
layout: project
title: VGAC
subtitle: VIIRS Global Area Coverage
permalink: /vgac/
featured_image: /assets/images/GulfCoast.jpg
image_caption: VGAC global coverage
related_links:
  - title: NOAA NCEI VGAC Page
    url: https://www.ncei.noaa.gov/metadata/geoportal/rest/metadata/item/gov.noaa.ncdc:C01703/html
  - title: Related Publications
    url: /publications/
---

## Overview

VIIRS Global Area Coverage (VGAC) is a comprehensive satellite climate data record that provides calibrated, quality-controlled observations from the Visible Infrared Imaging Radiometer Suite (VIIRS) instrument aboard multiple polar-orbiting satellites. VGAC serves as a critical component of NOAA's satellite climate data portfolio, designed to support long-term climate monitoring and research applications.

As a modern satellite data record, VGAC builds on decades of polar-orbiting satellite observations to create a consistent, well-calibrated dataset suitable for climate studies. The product leverages cloud-based processing architectures to ensure efficient, scalable data production and distribution.

## Data Access
### NCEI Archive
Operational and archived data at NCEI are available with a 3-5 week latency. Some of the data are available by 
[HTTPS download](https://www.ncei.noaa.gov/data/viirs-global-area-coverage/access/)

For the entire archive period of record, users would need to contact NCEI directly: ncei.orders@noaa.gov

### Operational updates
The archived data were routinely produced and made  by NOAA STAR in coordination with the University of Maryland until January 2026. Their latency issporadic (performing updates every 2-4 weeks). Their anonymous FTP server provides access to historic data:  
ftp://snpp.umd.edu/VGAC/

Since January 2026, the operational and archived data are produced by and available from NCICS (in cooperation with NCEI). The data are available generally with a 3 hour latency at their anonymous FTP server:  
ftp://filsrv.cicsnc.org/vgac/data/

## Presentations and papers
* [VGAC presentation at 2026 AMS Annual Meeting](/assets/files/AMS VGAC presentation 12.1.pdf)

## Data Description
VGAC integrates observations from multiple VIIRS instruments on operational polar-orbiting satellites, including:

- **Suomi NPP** (NOAA-20): Provides continuous global coverage with advanced radiometric capabilities
- **JPSS Series**: JPSS-1, JPSS-2, and future missions ensuring long-term data continuity
- **Global Coverage**: Near-global observations with polar-orbiting satellite swaths

The dataset undergoes rigorous calibration and quality control procedures to ensure consistency across different satellite platforms and instrument generations. Data processing implements:

- Inter-satellite calibration for seamless multi-platform integration
- Robust quality assurance procedures for operational data validation
- Modern cloud-based processing infrastructure for efficient data handling
- Integration with NOAA data distribution systems for broad accessibility

## Applications

VGAC supports a wide range of scientific and operational applications:

- **Climate Record Development**: Long-term, consistent observations for climate trend analysis and monitoring
- **Environmental Monitoring**: Tracking changes in Earth's atmosphere, land surface, and oceans
- **Research Support**: Providing validated satellite data for academic and scientific research
- **International Coordination**: Supporting collaborative efforts with international partners including EUMETSAT
- **Data Continuity**: Ensuring seamless transition between satellite generations for uninterrupted climate records

The standardized calibration and global coverage make VGAC particularly valuable for studies requiring consistent observations over extended time periods.

## Technical Details

VGAC employs modern data processing approaches optimized for climate data record production:

- **Processing Architecture**: Python-based algorithms deployed in cloud environments (AWS)
- **Scalability**: Designed for routine operational processing with parallel processing capabilities
- **Quality Control**: Comprehensive validation frameworks ensuring data integrity
- **Data Stewardship**: Follows NOAA Climate Data Record standards and best practices
- **Integration**: Compatible with existing NOAA Open Data Dissemination (NODD) systems

The technical implementation emphasizes practical solutions that bridge research innovation with operational requirements, ensuring sustainable long-term production of this critical climate dataset.