# An application of item response theory for agricultural sustainability measurement
## Sample code and data

This repository provides the code and sample data needed to test the proposed method for generating an agricultural sustainability index using item response theory. A working version of the manuscript can be found at SSRN [here](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4457489). The files required to run the model are as follows:

- ```supplementary_materials.pdf``` is an amendment to the manuscript that contains a literature review of indicators for agricultural sustainability indices, as well as descriptions and the calculations used to generate all items for the index. The STATA code used to generate the items described in this document can be found [here](https://github.com/brianbeadle/sustainability_index), but would require access to farm-level FADN data 
- ```(filename)``` contains the sample data for the index. The data are in longitudinal format and contain the following variables:
  - ```id``` is a randomly generated farm id
  - ```item``` is a categorical variable denoting the item number (item descriptions and calculations are provided in the supplementary materials)
  - ```y``` is the observed response
  - ```TF8``` denotes the type of farm (see supplementary materials or FADN documentation for definitions)
  - ```A26``` identifies the economic size class of the farm (see supplementary materials or FADN documentation for definitions)
- ```200-IRM-cs-2013-priors.Rmd``` is the R code used to generate the agricultural sustainability index using the ```brms``` package
- ```200-IRM-cs-2013-priors-experiements.Rmd``` is a test model removing the priors in the previous model
- ```170-asi-results-cs.do``` contains the STATA code used to generate robustness tests and visuals used in the paper 
