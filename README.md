# spalling-db-draft
This is a draft to be presented during RILEM meeting, Anglet, March 2026

[![DOI](https://zenodo.org/badge/1186265714.svg)](https://doi.org/10.5281/zenodo.19111378)




## CONCRETE SPALLING LIBRARY

## Overview
This repository contains a database of experimental results related to concrete spalling under high temperature conditions. 
The database compiles information from published studies and laboratory tests in order to support research on fire behaviour of concrete.

## Purpose
The main objective of this database is to:
- collect experimental data on concrete spalling,
- allow comparison of different concrete compositions and test conditions,
- support development and validation of predictive models.

## Database Content
The database includes the following parameters:

- concrete composition (cement type, aggregates, additives, fibres)
- water-to-cement ratio
- specimen geometry and dimensions
- heating rate and temperature exposure
- test method
- presence and type of spalling
- depth or mass loss caused by spalling
- reference to the original publication

## Structure of the Database

| Column name | Description |
|-------------|-------------|
| ID | Unique identifier of the test |
| Reference | Source publication |
| Concrete type | Description of the concrete mixture |
| w/c ratio | Water-to-cement ratio |
| Fibres | Type and amount of fibres |
| Heating rate | Temperature increase rate (°C/min) |
| Max temperature | Maximum exposure temperature (°C) |
| Specimen size | Dimensions of the tested sample |
| Spalling | Occurrence of spalling (Yes/No) |
| Spalling depth | Depth of material loss (mm) |

## Data Sources
Data were collected from:
- scientific journal articles
- conference proceedings
- experimental research reports

Each record includes a reference to the original source.

## Usage
The database can be used for:
- statistical analysis of spalling behaviour
- development of predictive models
- comparison of experimental results from different studies

## Limitations
The database compiles results from different experimental setups, which may lead to variability in testing conditions and measurement methods.

## License
Specify the license under which the data are shared (e.g. CC BY 4.0).

