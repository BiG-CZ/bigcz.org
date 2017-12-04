---
layout: default
title: Catalog
---

# BiG CZ Data Catalog

The BiG CZ Data Catalog is designed to bridge data systems developed for multiple critical zone domains by providing a single search interface of multiple data catalogs through the BiG CZ Data Portal, which can help discover datasets to visualize directly in the BiG CZ Data Portal or further explored with the BiG CZ Data Toolbox. The BiG CZ Data Catalog work also includes the development of web service APIs for ODM2 databases, to enable public cataloging, discovery and access of datasets in open ODM2 database instances.

## Catalogs for BiG CZ

Three different catalogs can simultaneously be searched within the the BiG CZ Data Portal, at <https://portal.bigcz.org>:

- **CINERGI.** The Community Inventory of EarthCube Resources for Geosciences Interoperability (CINERGI) Data Portal is a catalog of databases, services and data portals developed by numerous organizations representing a diversity of geoscience domains. Explore CINERGI at <http://cinergi.sdsc.edu/>
- **HydroShare:** HydroShare is an online collaborative environment for sharing hydrologic data and models. Its goal is to facilitate creation, collaboration around, discovery and access to data and model resources shared by members of the Hydrology community. See <https://www.hydroshare.org/>
- **CUAHSI Water Data Center (WDC):** The Consortium of Universities for the Advancement of Hydrologic Science, Inc. (CUAHSI) Water Data Center (WDC) provides tools for data access, analysis and collaboration, including a Catalog of hydrological time series data available as Water One Flow (WOF) and WaterML web services. See <https://www.cuahsi.org/data-models/discovery-and-analysis/>

## Web Service APIs

- RESTful web services have been for sharing data from an ODM2 database via web protocols such as CUAHSI HIS WaterOneFlow compliant web services for serving observational time series data as WaterML 1.1 and WaterML 2.0 (<https://github.com/ODM2/WOFpy>, fully functional). In addition, we are developing a new, prototype REST web services for serving datasets derived from physical samples and time series from ODM2 database instances (<https://github.com/ODM2/ODM2RESTfulWebServices>, under development). These web services go beyond the capabilities of the CUAHSI HIS web services, which do not adequately support the publication and access to observations and metadata derived from physical samples, which are central to CZ datasets and critical to the function of BiG-CZ Central.