---
layout: project
title: VGAC
subtitle: VIIRS Global Area Coverage
permalink: /vgac/
featured_image: /assets/images/Texas.png
image_caption: VGAC global coverage
related_links:
  - title: NOAA NCEI VGAC Page
    url: https://www.ncei.noaa.gov/metadata/geoportal/rest/metadata/item/gov.noaa.ncdc:C01703/html
  - title: Related Publications
    url: /publications/
---

## Overview

VIIRS Global Area Coverage (VGAC) is a comprehensive satellite record that provides reprojected data from the Visible Infrared Imaging Radiometer Suite (VIIRS) instrument aboard multiple polar-orbiting satellites. VGAC serves as a critical component of NOAA's satellite climate data portfolio, designed to extend the life of historic CDRs therby supporting long-term climate monitoring and research applications.

The product leverages cloud-based processing architectures to ensure efficient, scalable data production and distribution.

## Data Access
### NCEI Archive
Operational and archived data at NCEI are available with a 3-5 week latency. Some of the data are available by 
[HTTPS download](https://www.ncei.noaa.gov/data/viirs-global-area-coverage/access/)

For the entire archive period of record, users would need to contact NCEI directly: ncei.orders@noaa.gov

### Routinely updated data
The operational and archived data are produced by and available from NCICS (in cooperation with NCEI). The data are available generally with a 3 hour latency at their anonymous FTP server:  
**ftp://filsrv.cicsnc.org/vgac/data/**

Data will also likely be available on NODD (NOAA Open Data Dissemination)

## Presentations and papers
* [VGAC presentation at 2026 AMS Annual Meeting](/assets/files/AMS VGAC presentation 12.1.pdf)

## Data Description
The data are reprojected to provide a product similar to legacy AVHRR GAC data. This includes:
- Files organized by orbit (instead of by granule).
- Channels provided at 3.9 km resolution (which approximates the original GAC resolution)

Data are routinely produced for NOAA 20 and 21.

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
- **Integration**: Compatible with existing NOAA Open Data Dissemination (NODD) systems

The technical implementation emphasizes practical solutions that bridge research innovation with operational requirements, ensuring sustainable long-term production of this critical climate dataset.