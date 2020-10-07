# Demographic_Analysis_of_Brexit
This repository contains the files related to a project with the goal of analyzing the demographic breakdown of different wards in the United Kingdom with respect to their respective outcomes in the 2016 Brexit referendum.

---
## Folders
### data
This folder contains the various datasets used in the project. The external folder contains the following:

- fetzer_study_data.dta: This file contains data from [this paper](https://ideas.repec.org/a/oup/ecpoli/v32y2017i92p601-650..html). This is the main dataset used for the analysis and modelling in this project. Each instance is a ward in the United Kingdom, and the features include demographic information such as age, income, and proportion of migrants in the population.

- postcodes.csv: This file contains geographic information on wards in the United Kingdom. This is only for the purpose of vizualization.

- ward-results.xlsx: This file contains the Brexit results for each ward in the United Kingdom.


The processed folder contains intermediate datasets I created in the course of the project:

- fetzer_processed_data.csv: This file is simply the data from the paper by Fetzer et al processed for modelling.

- ward_atlas_data.csv: This file is a combination of postcodes.csv and ward-results.xlsx for the purpose of creating a vizualization and a dashboard on Tableau.


### notebooks
This folder contains the code for the project:

- initial_analysis: This folder contains my initial analysis and preparation of the data for modelling and vizualization.

- modelling: This folder contains various notebooks trying different models. The most effective model is contained in ensembling.ipynb


### slides
This folder contains the slide deck I used when presenting on this project.


### vizualization
This folder contains a Tableau map vizualization showing the different results across the UK, and also a Tableau dashboard I created to present my various findings.
