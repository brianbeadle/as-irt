## An application of item response theory for agricultural sustainability measurement
### Sample code and data

This repository contains the code and sample data to test the method proposed to generate an agricultural sustainability index using item response theory. The files required to run the model are as follows:

- ```(filename)```: The sample data for the index. The data are in longitudinal format and contain the following variables:
  - ```var1``` is a randomly generated farm id
  - ```item``` is a categorical variable denoting the item number (item descriptions and calculations are provided in the supplementary materials)
  - ```y``` is the observed response
  - ```tf8``` denotes the type of farm (see supplementary materials or FADN documentation for definitions)
  - ```a26``` identifies the economic size class of the farm (see supplementary materials or FADN documentation for definitions)
- ```(filename)```: is the R code used to generate the agricultural sustainability index
- ```(filename)```: contains the STATA code used to generate robustness tests and visuals used in the paper 
