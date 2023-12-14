# Landcover Classification for Southern Santa Barbara County
A repository to run an analysis utilizing Landsat data for Santa Barbara County in order to train and apply a decision tree classifier for landcover types.

## Purpose

Monitoring the distribution and change in land cover types can help us understand the impacts of phenomena like climate change, natural disasters, deforestation, and urbanization. Determining land cover types over large areas is a major application of remote sensing because we are able to distinguish different materials based on their spectral reflectance.

Classifying remotely sensed imagery into landcover classes enables us to understand the distribution and change in landcover types over large areas. 

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
