# WB_paper_public
code from ‘Potentially harmful World Bank projects are proximate to and areas of biodiversity conservation importance’

This directory contains the jupyter notebooks to reproduce the analysis in the Global Environmental Change paper:

 Potentially harmful World Bank projects are proximate to and areas of biodiversity conservation importance

## Python folder
 The bases_projects notebook creates reference rasters at 5, 10, 25 and 50 km resolutions and assigns points presenting project activities with cell values for each resolution. This cell values are later used to aggregate the dataset
 The species notebook creates rasters with the count of overlapping ranges of globally threatened birds, mammals, and amphibians.
 The bio_areas notebook creates rasters with the presence or absence of a biodiversity hotspot, Protected area or Key Biodiversity Area

## R folder
 The models_5km notebook creates the final dataset, runs the three series of models, produces summary figures and conducts sensitivity analysis.

## Figures
 Copies of output figures and others from the paper can be found here

## Data
In the data sub-directory there is a list of possible borrowers from the World Bank manually created from several sources. And a look up for information on each district code used to assign countries to raster cells.

Other data must be sourced from the original publishers:

 World Bank project dataset -  https://www.aiddata.org/data/world-bank-geocoded-research-release-level-1-v1-4-2
 
 Birds dataset can be requested here - http://datazone.birdlife.org/species/requestdis
 
 Mammals and amphibians - https://www.iucnredlist.org/resources/spatial-data-download
 
 KBA dataset can be requested here - http://datazone.birdlife.org/site/requestgis
 
 Protected areas - https://www.protectedplanet.net/en/thematic-areas/wdpa?tab=WDPA
 
 Biodiversity hotspots - https://zenodo.org/record/3261807#.YQlvkY5KiUn
 
 Countries and districts - https://gadm.org/
 
 Population data from here - https://sedac.ciesin.columbia.edu/data/set/gpw-v4-population-count-adjusted-to-2015-unwpp-country-totals-rev11/data-download
 
 Corruption Perception Index - https://www.transparency.org/en/cpi/2020/index/
 
 Gross National Income - https://databank.worldbank.org/reports.aspx?source=2&series=NY.GNP.PCAP.CD
