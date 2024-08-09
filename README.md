## An application of item response theory for agricultural sustainability measurement
### Sample code and data

This repository contains the code and sample data to test the method proposed to generate an agricultural sustainability index using item response theory. A working version of the manuscript can be found at SSRN [here](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4457489). The files required to run the model are as follows:

- ```supplementary_materials.pdf``` is an amendment to the manuscript that contains a literature review of indicators for agricultural sustainability indices, as well as descriptions and the calculations used to generate all items for the index. The STATA code used to generate the items described in this document can be found [here](https://github.com/brianbeadle/sustainability_index) 
- ```(filename)``` contains the sample data for the index. The data are in longitudinal format and contain the following variables:
  - ```id``` is a randomly generated farm id
  - ```item``` is a categorical variable denoting the item number (item descriptions and calculations are provided in the supplementary materials)
  - ```y``` is the observed response
  - ```TF8``` denotes the type of farm (see supplementary materials or FADN documentation for definitions)
  - ```A26``` identifies the economic size class of the farm (see supplementary materials or FADN documentation for definitions)
- ```(filename)```: is the R code used to generate the agricultural sustainability index
- ```(filename)```: contains the STATA code used to generate robustness tests and visuals used in the paper 
