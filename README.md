# bayes_study_of_covid19

**Purpose of the project**
This project contains files used in a study, from which the paper `A Bayesian spatio-temporal study of the association between meteorological factors and the spread of COVID-19' originated. This paper is currently available as a pre-print on arXiv.

**Description of project files**
- CasePopulationData.csv - CSV file containing population for all 312 Local Authority Districts (LADs) in England
- CleanWeatherData.rds - R object containing daily observed values of meteorological factors and COVID-19 case counts for English LADs
- LAD_(Dec_2020)_UK_BFC.zip - Shapefile of English LAD boundaries during the study period
- LoadData.Rmd - Loads data from CasePopulationData, CleanWeatherData and the Shapefile
- ExploratoryDataAnalysis.Rmd - Used to explore correlations between weather variables and spatio-temporal structure of case counts
- ParallelModel.Rmd - Runs a Bayesian spatio-temporal model with the W neighbourhood matrix
- SensitivityModel.Rmd - Runs a Bayesian spatio-temporal model with the W neighbourhood matrix 
- ParallelAnalysis.Rmd - Executes model diagnostics and studies the model posterior distributions
- RandomEffectAnalysis.Rmd - Further investigation of the model random effects that define correlations between neighbouring LADs
- W.rds - Neighbourhood matrix defining neighbouring LAD structure in England
  - Only adjacent LADs are neighbours  
- new_W.rds - Neighbourhood matrix defining neighbouring LAD structure in England
  - Adjacent LADs are neighbours
  - Additionally LADs in the largest metropolitan areas that share a common adjacent LAD are neighbours

**Have a question?**
If you have any questions, or would like to discuss the project please contact Jamie Mullineaux via james.mullineaux.21@ucl.ac.uk

**Terminology**
LAD - Local Authority District
