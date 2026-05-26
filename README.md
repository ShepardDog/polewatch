6o# Polewatch

![WIP](https://img.shields.io/badge/status-WIP-orange?style=flat-square)
![License: MIT](https://img.shields.io/badge/license-MIT-green?style=flat-square)
![🐾 For Arctic Foxes, Seals, Bears, and All Polar Life](https://img.shields.io/badge/%F0%9F%90%BE%20For-Arctic%20Foxes%2C%20Seals%2C%20Bears%2C%20and%20All%20Polar%20Life-0aa?style=flat-square)

**Polewatch** is a data-driven observatory for Earth’s cryosphere — documenting environmental, ecological, and climate-related change across both the Arctic and Antarctic. It serves as a long-term resource for researchers, journalists, conservationists, and citizen scientists committed to polar protection and planetary health.
This 44-table relational database architecture is designed to solve the critical bottleneck of data fragmentation in polar climate research. Currently, Arctic environmental indicators, satellite sea ice records, and marine wildlife biometric datasets are stored across isolated, multi-sector repositories. This project unifies those disjointed arrays into a single, scalable data warehouse to enable long-term, cross-variable trend analysis.


---

## 🌐 Overview

Polewatch unifies and standardizes polar data — from wildlife populations to sea ice dynamics — into a relational database optimized for:

- Ecological monitoring  
- Conservation insights  
- Climate anomaly detection  
- Policy-relevant reporting  
- Scientific collaboration  

This project was built with transparency, traceability, and public accessibility in mind.

---

## 🧊 Current Focus Areas

- **Arctic animal tracking** (e.g., foxes, seals, bears)  
- **Cryosphere datasets** (e.g., sea ice, temperature baselines)  
- **Threat monitoring** (e.g., oil extraction, industrial shipping)  
- **Habitat shifts and species survival data**  
- **Normalized region mapping for polar zones**
-  **Climate Variable Layer:** Tracks daily/monthly sea ice concentration metrics ($km^2$), sea surface temperatures (SST), and geospatial boundaries across distinct Arctic zones (e.g., Beaufort, Chukchi, and Laptev seas).
-  **Ecological Biometric Layer:** Stores historical population dynamics, reproductive success rates, migratory timelines, and physiological biometric records for key indicators (e.g., Ursus maritimus, Phocidae).

Coming soon: Antarctic expansion phase — including penguin colonies, glacial retreat, and climate-linked migration shifts.
The database utilizes a highly normalized SQL schema to cleanly link physical oceanographic changes with biological ecosystem responses. The 44 tables are structurally segmented into three core layers: 
*   **Anthropogenic Threat Layer:** Tracks commercial shipping lane traffic density, industrial resource extraction coordinates, and localized environmental policy dockets over a multi-decade timeline.

---

## 🛠️ Tech Stack

- PostgreSQL (PostGIS support coming soon)  
- Python (for data wrangling, APIs, and automation)  
- CSV, NetCDF (.nc), and satellite-derived data inputs  
- Custom SQL views and versioning logic  
- GitHub-hosted schema and documentation

To ensure data integrity and remove manual collection errors, the data ingestion pipeline leverages Python and Pandas to clean, format, and load incoming feeds:
1.  **Extraction:** Pulling automated public data streams from remote repositories via the National Snow and Ice Data Center (NSIDC) API.
2.  **Transformation (Pandas):** Standardizing spatial coordinates (Latitude/Longitude) into consistent coordinate reference systems (CRS) and normalizing varied temporal formats into strict ISO timestamps.
3.  **Loading:** Ingesting structured DataFrames directly into the relational SQL environment via automated database connection scripts.
---


## 📁 Repository Structure


## 📋 Current Milestone & Project Status
*   [x] Initial 44-table relational database schema design completed.
*   [ ] Automation of NSIDC data ingestion pipelines using Python Pandas (Active Phase).
*   [ ] Population of primary sea ice extent index metrics (Historical timeline: 1978–Present).
*   [ ] Generation of unified SQL queries correlating seasonal sea ice minimums with targeted population biometrics.


## I Built This
For the foxes, the wolves, the bears, the seals, the owls, the whales, and many other animals who cannot code, but still suffer the consequences of human actions and global warming.  
**To the Arctic species — with love.**
