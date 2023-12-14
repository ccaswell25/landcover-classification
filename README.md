# Landcover Classification for Southern Santa Barbara County
A repository to utilize Landsat data for Santa Barbara County in order to train and apply a decision tree classifier for landcover types.

## Purpose

Marine aquaculture has the potential to play an important role in the global food supply as a more sustainable protein option than land-based meat production.1 Gentry et al. mapped the potential for marine aquaculture globally based on multiple constraints, including ship traffic, dissolved oxygen, bottom depth .2

This analysis will look at which Exclusive Economic Zones (EEZ) on the West Coast of the US are best suited to developing marine aquaculture. First analyzed for several species of oysters, and then includes a function to understand results for a chosen marine species.

## Structure

```         
landcover-classification
│   README.md
│   Rmd/Proj files    
│   .gitignore
└───data
    │   SB_county_south.shp
    │   LT05_L2SP_042036_20070925_20200829_02_t1_SR_B1.tif
    |   LT05_L2SP_042036_20070925_20200829_02_t1_SR_B2.tif
    |   LT05_L2SP_042036_20070925_20200829_02_t1_SR_B3.tif
    |   LT05_L2SP_042036_20070925_20200829_02_t1_SR_B4.tif
    |   LT05_L2SP_042036_20070925_20200829_02_t1_SR_B5.tif
    |   LT05_L2SP_042036_20070925_20200829_02_t1_SR_B7.tif
    │   trainingdata.cpg
    │   trainingdata.dbf
    |   trainingdata.prj
    |   trainingdata.qpj
    |   trainingdata.shp
    |   trainingdata.shx

```

## Set-up

Data associated with this analysis is too large to be included in the repository. It was downloaded and stored locally and included in the .gitignore. You can find details on the data files included in the R markdown file.
