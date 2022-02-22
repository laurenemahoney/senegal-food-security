# Mapping Hotpots of Food Insecurity in Senegal
This repository contains spatial mapping products for our analysis of spatial hoptspots of food security in Senegal as well as potential linkages with climatic drivers. This work was conducted as a part of a summer internship with the International Research Institute for Climate and Society (IRI) ACToday Senegal division in partnership with the World Food Programme (WFP) Vulnerability and Assessment Mapping (VAM) unit. 

## Datasets Used: 
The data used in this analysis include:
* WFP VAM Survey Data: Household survey data collected internmittently by various intergovernmental organizations from 2009-2019, and gathered by WFP for a Comprehensive Food Security and Vulnerability Analysis (CFSVA). Measured food insecurty by 3 Indices: the Food Consumption Score (FCS), the Food Expenditure Share (FES) and the Reduced Coping Strategies Index (rCSI); Accessed through the IRI Data Library. 
* Precipitation Data: ANACIM Daily timeseries dataset aggregated over department; *1981-2016*; Measured wet spells, dry spells, and rainfall onset. Reconstructed rainfall on a 0.0375 x 0.0375 lat/lon grid (about 4km) by combining quality-controlled station observations in ANACIM's archive with satellite rainfall estimates [available here](http://213.154.77.59/maproom/Climatology/Climate_Analysis/daily_precip.html)
* Disaster Data: Flood and drought data from DesInventar available from *1993-2014*; DesInventar Dry Spell data only for 2013 and 2014 years; EMDAT from *2008- present* [available here](https://www.desinventar.net/) and [here](https://public.emdat.be/)
* Food Price Data: WFP Monthly data for the period *2000-2020* at the market level.
* Food Production Data: WFP Crop yield dataset of all cereals in Senegal  at the department level, for the period *1961-2013*.

## Objectives: 
Can WFP VAM survey data be used to understand particularized hotspots of food insecurity in Senegal, and can these hotspots be impacted by climate drivers and natural disasters? 
* Where are food insecure hotspots located in Senegal? In what context?
* Why do these hotspots of food insecurity exist? 

## Summary of Results: 
### Where are food insecure hotspots? 
* Changes in FCS intensity (high vs. lower scores) and spatial patterns prevalent over duration of 4 survey years (2010- 2019)
* Prevalence of more extreme food insecurity per department varies amongst survey years with 2013 and 2014 showing the highest % of HH in the top FCS quantile
* Overall, food insecurity (low FCS) is highest in the South in the Casamance and Kedougou regions 

<img src="https://github.com/laurenemahoney/senegal-food-security/blob/main/outputs/figures/Senegal_VAM_2014_FCS_Map_FINAL.png" width="50%">
<img src="https://github.com/laurenemahoney/senegal-food-security/blob/main/outputs/figures/Senegal_VAM_2014_Fraction20_Map_FINAL.png" width="50%">

*(Top) Spatial map of 2014 Food Consumption Scores (FCS), a measure of food security where low FCS translate to high food insecurity. (Bottom) Spatial map of the fraction of households in 2014 in the top 20 quantile of FCS, a measure of the most food insecure households.*

<img src="https://github.com/laurenemahoney/senegal-food-security/blob/main/outputs/figures/Senegal_VAM_2014_Disasters_Map_FINAL.png" width="50%">
<img src="https://github.com/laurenemahoney/senegal-food-security/blob/main/outputs/figures/Senegal_VAM_2014_Total_Map.png" width="50%">

*(Top) Spatial map of natural disasters occuring in 2014, including flooding, drought, and a dry spell. (Bottom) Map of total number of households surveyed in 2014.*

### Why do these hotspots of food insecurity exist? 
#### Connections to Precipitation 
<img src="https://github.com/laurenemahoney/senegal-food-security/blob/main/outputs/figures/bignona_timeseries.png" width="50%">
<img src="https://github.com/laurenemahoney/senegal-food-security/blob/main/outputs/figures/precipitation_annomaly.png" width="50%">

