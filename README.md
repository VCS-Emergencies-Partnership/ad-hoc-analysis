# Ad Hoc 

## Overview
This repo is a space for the VSCEP/RBC insight team to run ad hoc analyses. Each ad hoc analysis should be a self contained folder in the `analysis/` directory. All old files have been moved to depreciated, keeping the old folder structure intact.


## Analysis

### Data quality

This folder contains code to run pandas profiling code on a single file (or a set of files within a folder). It is currently for csv files but can be amended to also cover other types of files. It saves the pandas profiling reports for the datasets into a older. The `instructions` file contains instructions of how to run the code. 

If you wish to create a pandas profiling report on a csv file not using code Mike Page has created a Shiny app where can upload the file and the report outputs directly [here](https://github.com/MikeJohnPage/shiny-panda). 

### Local capability mapping mockup 

This contains code for a Shiny app created to demo what the local capability mapping project output could look like. The data used is mock data. 

### VCSEP regions boundaries

The VCSEP regional boundaries changed as Thames Valley area moved from the South East to the South West. 

### Testing lookup methods

Ahead of new search functionality for geographical areas in future Shiny Apps testing time taken for different approaches of lookup methods (dplyr::filter, data.table, hashtables). 