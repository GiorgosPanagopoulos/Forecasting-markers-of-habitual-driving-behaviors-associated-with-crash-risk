# Forecasting markers of habitual driving behaviors associated with crash risk

Code to reproduce the analysis of the paper ["Forecasting markers of habitual driving behaviors associated with crash risk"](https://ieeexplore.ieee.org/document/8695787).  <br />

The folder structure of the project to reproduce the analysis should be like this:  <br />

### Folder Structure

Code-> ( Fill it with this code ) <br />
Data-> Raw ( fill it with the data found under Raw Thermal Data folder in https://osf.io/c42cn/) <br />
Data-> Dataset-Table-Index.csv<br />
Data-> Results (will be filled by the scripts)<br />
Figures (will be filled by the scripts)

### Requirements
R libraries <br>
signal, dplyr,xlsx,TTR,pastecs,ggplot2,caret,zoo,tibble,lomb,reshape2,glmnet,xgboost,ROCR,pROC


### Run Instructions
Each script can be run individually, following the order of the number in the script's title.  <br>
If two scripts have the same number, they can be run simultaneously.  <br>
Data visualization app can be accessed here https://georgepanagopoulos.shinyapps.io/ForecastRoadBehavior
