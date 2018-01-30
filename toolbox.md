---
layout: default
title: Toolbox
---

# BiG CZ Data Toolbox

The BiG CZ Data Toolbox is a single, easy-to-install, easy-to-teach cross-platform package of the ODM2 software ecosystem and power functions for accessing [BiG CZ Data Catalog](http://bigcz.org/catalog) and Web services.

<img src="https://github.com/BiG-CZ/bigcz.org/blob/master/assets/img/ODM2-Tools-Screenshot2-PowerFunctions.png?raw=true" align="right" width="300">

It will serve cyber-savvy CZ scientists with powerful tools for local data management and publication and for access, analysis and modeling of data available via the [BiG CZ Data Portal](http://bigcz.org/portal/) and other data repositories.

The BiG CZ Data Toolbox is an easy-to-install software system that includes graphical user interface (GUI) applications within an independent Python environment built upon the Conda packaging system and Conda virtual environments.

This collection of software was showcased at our capstone [2017 BiG-CZ / ODM2 Hands-On Workshop](https://github.com/BiG-CZ/bigcz_wshp2017). The complete content of the workshop, including slides, walk-through examples and installation packages, is available at https://github.com/BiG-CZ/bigcz_wshp2017.

## BiG CZ Data Toolbox Components

### ODM2 Database

A ready-to-use relational database based on ODM2 implemented in SQLite, Microsoft SQL Server, MySQL or PostgreSQL (<https://github.com/ODM2/ODM2>) and pre-populated with ODM2 Controlled Vocabularies (<http://vocabulary.odm2.org>).

Extensive ODM2 documentation and scripts for creating ODM2 relational databases are available now.

- Website: <http://www.odm2.org/>
- ODM2 Documentation Wiki:
  - Information on ODM2 concepts, examples, best practices, the ODM2 software ecosystem, etc.
  - <https://github.com/ODM2/ODM2/wiki/documentation>
- ODM2 Entity Relationship Diagrams
  - Schema diagrams for the current version of the ODM2.
  - <http://ODM2.github.io/ODM2/schemas/ODM2_Current/>
- ODM2 on GitHub
  - <https://github.com/ODM2/odm2-software-ecosystem>
- Additional documentation on ODM2 software components is available in the respective repository.

### ODM Tools Python

<img src="https://github.com/BiG-CZ/bigcz.org/blob/master/assets/img/ODM2-Tools-Screenshot1-TimeSeriesFunctions.png?raw=true" align="right" width="300">

ODM Tools time series exploration.
A GUI desktop application for visualization and scripted quality control of environmental sensor observations data. Fully functional with ODM 1.1. ODM2 support has been added and is currently being tested.  <https://github.com/ODM2/ODMToolsPython>.

### ODM2 Web Services

Web services for sharing data from an ODM2 database using:

* **Water One Flow / WaterMLv1.1 web services** (SOAP & REST) to read time series data from ODM2 
  * WOFpy: <https://github.com/ODM2/WOFpy> (fully functional)
  * Explore our WOFpy deployment at: <http://data.envirodiy.org/wofpy/>
* **ODM2 RESTful Webservices** to read & write all data in ODM2
  * ODM2RESTfulWebServices: <https://github.com/ODM2/ODM2RESTfulWebServices> (under development)
  
### BiG CZ Jupyter Notebooks
These Jupyter Notebooks in Python and R demonstrate and teach BiG CZ & ODM2 software and database use, and were used as training materials for the capstone [2017 BiG-CZ / ODM2 Hands-On Workshop](https://github.com/BiG-CZ/bigcz_wshp2017):

* <https://github.com/BiG-CZ/wshp2017_tutorial_content/tree/master/notebooks>
* <https://github.com/BiG-CZ/BiG-CZ-Toolbox/tree/master/ipynotebooks>

For a complete set of hands-on materials from the workshop, including all notebook files, supporting code, data files, and Conda environment files, `git` clone the following repository:

* <https://github.com/BiG-CZ/wshp2017_tutorial_content>

### ODM2 Dataset Ingest via YODA-Tools

The [YODA Tools](https://github.com/ODM2/YODA-Tools) library, which is built upon the [ODM2PythonAPI](https://github.com/ODM2/ODM2PythonAPI), was developed to ingest datasets from our [YODA Excel Templates](https://github.com/ODM2/YODA-File/tree/master/excel_templates) and load these datasets into ODM2. YODA Tools has a simple desktop application, in addition to providing all functions in Python.

Read more at <https://github.com/BiG-CZ/bigcz_wshp2017/blob/master/Topics/5-ODM2DatasetsYODAspreadsheets.md>.


### ODM2 Conda Channel

The ODM2 Conda Channel provides easy-to-install options for installing our ODM2 Python libraries or a customized environment for the Anaconda or Miniconda scientific Python distribution.

* ODM2 Conda Channel: <https://anaconda.org/odm2>
* Instructions: <https://github.com/BiG-CZ/wshp2017_tutorial_content/blob/master/install-conda.md>

