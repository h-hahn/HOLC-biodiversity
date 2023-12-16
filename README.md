# The Impact of Historical HOLC Redlining on Living Conditions and Biodiversity

## Overview
This repository contains an analysis on redlining in Los Angeles and how it impacts living conditions and biodiversity. Using EJScreen, historical redlining, and biodiversity observation data, I look at the relationship between historical redlining neighbourhoods and how it impacts the the living conditions of census groups living there today. Additionally, using bird observation data, I look at how biodiversity observations differ among historically redlining census block groups.

This analysis allows us to understand how historical patterns of injustice shapes demographic and environmental conditions of today.

## About the Data
**EJScreen**

Data from the United States Environmental Protection Agency's EJScreen: Environmental Justice Screening and Mapping Tool. EJScreen provides on environmental and demographic information for the US at the Census [tract](https://en.wikipedia.org/wiki/Census_tract) and [block group](https://en.wikipedia.org/wiki/Census_block_group) levels. 

**Mapping Inequality**

A team of researchers, led by the [Digital Scholarship Lab](https://dsl.richmond.edu/) at the University of Richmond have digitized maps and information from the HOLC as part of the [Mapping Inequality](https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58) project.

[^5]: Robert K. Nelson, LaDale Winling, Richard Marciano, Nathan Connolly, et al., "Mapping Inequality," American Panorama, ed. Robert K. Nelson and Edward L. Ayers, accessed October 17, 2023, <https://dsl.richmond.edu/panorama/redlining/>

**Biodiversity observations**

The [Global Biodiversity Information Facility](gbif.org) is the largest aggregator of biodiversity observations in the world. Observations typically include a location and date that a species was observed. 

The data files were too large to be pushed to this repository, but can be accessed [here](https://drive.google.com/file/d/1lcazRbNSmP8Vj9sH1AIJcO4D1d_ulJij/view?usp=share_link) to save locally.
The redlining data can be read in using this link: https://dsl.richmond.edu/panorama/redlining/static/citiesData/CALosAngeles1939/geojson.json.

### Structure
The structure of the repo is:
> ```
> HOLC-biodiversity
> │   README.md
> │   HOLC-biodiversity.Rproj
> │  .gitignore
> └───documents
>    │   holc-biodiversity.html
>    │   holc-biodiversity.Rmd
> ```
The full analysis is contained in the documents folder in the .Rmd file.
