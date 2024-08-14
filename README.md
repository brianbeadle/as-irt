# An application of item response theory for agricultural sustainability measurement

This repository contains the code and supplementary materials necessary to replicate the Item Response Theory (IRT) model used for generating an agricultural sustainability index.

## List of replication files and description of each:

- The Farm Accountancy Data Network (FADN) data used in this study are officially available only to registered users. For complete documentation and conditions of access, please refer to [this link](https://agriculture.ec.europa.eu/data-and-analysis/farm-structures-and-economics/fadn_en). Given access to the original FADN files, the dataset can be replicated using the supplementary information provided in the file `01-supplementary_materials.pdf` within this repository. This supplementary document is an amendment to the manuscript and includes a literature review of indicators for agricultural sustainability indices, as well as detailed descriptions and calculations used to generate all items for the index.
- Data dictionary for the FADN data set:

| Variable | Description                                                                                                                    |
|:---------|:-------------------------------------------------------------------------------------------------------------------------------|
| `id`     | randomly generated farm id                                                                                                     |
| `item`   | categorical variable denoting the item number (item descriptions and calculations are provided in the supplementary materials) |
| `y`      | observed response                                                                                                              |
| `TF8`    | type of farm (see supplementary materials or FADN documentation for definitions)                                               |
| `A26`    | economic size class of the farm (see supplementary materials or FADN documentation for definitions)                            |
| `NUTS2`  | indicator for region (NUTS-2 regions)                                                                                          |

- The R Markdown file `02-IRT-models-estimations.Rmd` contains the code for estimating the IRT models used in the paper. It generates the results presented in Figures 2 through 4.
- The HTML file `02-IRT-models-estimations.html` displays the output of the knitted R Markdown file, including both the results and the R code, in an HTML format.

