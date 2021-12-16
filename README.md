## :open_file_folder: Data for Exercises <img src="img/icon-ursus.png" height="120" align="right"/>

[![License: CC
BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgreen.svg)](https://choosealicense.com/licenses/cc-by-4.0/)

<br /><br />

This repository contains the data used during the exercises of the workshop 
:mortar_board: 
[**_Data Toolbox for Reproducible Research in Ecology_**](https://rdatatoolbox.github.io) 
co-organized by the 
[FRB-CESAB](https://www.fondationbiodiversite.fr/en/about-the-foundation/le-cesab/) 
and the 
[GdR EcoStat](https://sites.google.com/site/gdrecostat/).


<br />

### Content

<br />

- **WWF Wildfinder** [:globe_with_meridians:](https://www.worldwildlife.org/pages/wildfinder-database)

The WWF WildFinder database contains the presence of World vertebrate species (Amphibians, Reptiles, Birds, and Mammals) in each terrestrial ecoregions. The folder `data/wwf-wildfinder/` only contains data for mammal species (4936 species) spread into three csv files:

  - `wildfinder-mammals_list.csv` : taxonomy of the 4936 mammal species
  - `wildfinder-ecoregions_list.csv` : information about the 798 terrestrial ecoregions
  - `wildfinder-ecoregions_species.csv` : correspondence between species and ecoregions

> **Citation:** World Wildlife Fund (2006) _WildFinder: Online database of species distributions_. Version Jan-06. URL: https://www.worldwildlife.org/pages/wildfinder-database.

<br />

- **PanTHERIA** [:globe_with_meridians:](https://esajournals.onlinelibrary.wiley.com/doi/10.1890/08-1494.1)

A global species-level data set of key life-history, ecological and geographical traits of all known extant and recently extinct mammals compiled from the literature. This database is stored in the file  `data/pantheria-traits/PanTHERIA_1-0_WR05_Aug2008.txt`. Missing data are noted `-999`.

> **Citation:** Jones KE _et al._ (2009) PanTHERIA: a species-level database of life history, ecology, and geography of extant and recently extinct mammals. **Ecology**, _90_, 2648. DOI: [10.1890/08-1494.1](https://doi.org/10.1890/08-1494.1).
