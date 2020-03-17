# Coronavirus data analysis

This repository contains a few Jupyter notebooks for investigating the COVID-19 data. Feel free to fork and add your own notebooks! 🦠😷

## Binder

You can directly launch the scripts with Binder.

Launch the **comparison**: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lukasmu/coronavirus/master?filepath=coronavirus_comparison.ipynb)

Launch the **forecast**: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/lukasmu/coronavirus/master?filepath=coronavirus_forcecast.ipynb)

## Background

From the [CDC](https://www.cdc.gov/coronavirus/2019-ncov/about/index.html):

> 2019 Novel Coronavirus (2019-nCoV) is a virus (more specifically, a coronavirus) identified as the cause of an outbreak of respiratory illness first detected in Wuhan, China. Early on, many of the patients in the outbreak in Wuhan, China reportedly had some link to a large seafood and animal market, suggesting animal-to-person spread. However, a growing number of patients reportedly have not had exposure to animal markets, indicating person-to-person spread is occurring. At this time, it’s unclear how easily or sustainably this virus is spreading between people.  The latest situation summary updates are available on CDC’s web page 2019 Novel Coronavirus, Wuhan, China.

This is an emerging, rapidly evolving situation and CDC will provide [updated information](https://www.cdc.gov/coronavirus/2019-ncov/summary.html) as it becomes available.

## Data

The data is provided by the [Johns Hopkins Center for Systems Science and Engineering](https://systems.jhu.edu/research/public-health/ncov/). They have created an interactive [GIS Dashboard](https://gisanddata.maps.arcgis.com/apps/opsdashboard/index.html#/bda7594740fd40299423467b48e9ecf6).
When running the notebooks the data is fetched from their [GitHub repository](https://github.com/CSSEGISandData/COVID-19). A backup is also available in the data folder.

> In response to this ongoing public health emergency, we developed an online dashboard (static snapshot shown below) to visualize and track the reported cases on a daily timescale; the complete set of data is downloadable as a google sheet. The case data visualized is collected from various sources, including WHO, U.S. CDC, ECDC China CDC (CCDC), NHC and DXY. DXY is a Chinese website that aggregates NHC and local CCDC situation reports in near real-time, providing more current regional case estimates than the national level reporting organizations are capable of, and is thus used for all the mainland China cases reported in our dashboard (confirmed, suspected, recovered, deaths). U.S. cases (confirmed, suspected, recovered, deaths) are taken from the U.S. CDC, and all other country (suspected and confirmed) case data is taken from the corresponding regional health departments. The dashboard is intended to provide the public with an understanding of the outbreak situation as it unfolds, with transparent data sources.
