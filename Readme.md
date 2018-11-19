## Final Project Description


#### Theresa Sawi  
##### tms2193




###  Are Greenland Glacial Earthquakes Remotely Triggered by Major Earthquakes? 


Large calving events in marine-terminating glaciers produce vibrations in the solid earth known as "glacial earthquakes", detectable at large distances and cataloged by the Harvard's Global CMT (from 1993-2013). I want to investigate if major (M>8) earthquakes around the globe can trigger the occurrence of glacial earthquakes at Greenland. I will use the Global CMT catalog of glacial earthquakes as well as the USGS global M>8 earthquakes (from 1993-2013) to investigate any possible temporal correlations between the two groups.

#### Data: 
[Global CMT catalog of glacial earthquakes (from 1993-2013)](https://www.ldeo.columbia.edu/~gcmt/projects/CMT/catalog/GLEA/GLEA_1993_2013_merged.txt)  
  
[USGS global M>8 earthquakes 		    (from 1993-2013)](https://earthquake.usgs.gov/fdsnws/event/1/query?format=csv&starttime=1993-01-01&endtime=2013-12-31&minmagnitude=8)  
  
    
 
 

#### File structure  
 .
├── data  
│   ├── balancevelo  
│   ├── basalThermalState  
│   ├── eqs  
│   └── surfaceMelt  
├── literature  
└── notebooks  
    └── classnotes  




######## previous idea -- but having trouble getting spatial data to work! Maybe I can get help with this...############


### Greenland Ice Sheet Calving Vulnerability Analysis 

~ or, time permitting ~

### Using Machine Learning to Predict Calving Vulnerability at the Greenland Ice Sheet


Large calving events in marine-terminating glaciers produce vibrations in the solid earth known as "glacial earthquakes", detectable at large distances and cataloged by the Harvard's Global CMT.   
  
I plan to use this catalog of glacial earthquakes, along with maps of estimated ice properties (velocity, basal thermal state, and surface melt) in order to investigate correlations between the ice properties and locations of the glacial earthquakes in the Greenland Ice Sheet.  
  
*(1) I will split the earthquake data into two parts; a training set to help build a 'glacial earthquake vulnerability map', and a testing set to test the predictive power of this vulnerability map.   
  
*(2) The 'glacial earthquake vulnerability map' will be formed by weighting and then combining the ice properties maps, using the seismic training set to empirically tune the weights.*(time permitting, this could be done using a Random Forest Algorithm, see below). It will be averaged over time (not exactly sure how yet -- seasonally perhaps), and simplified into a binary "glacial earthquake will or will not occur here" map.  
  
*(3) I will then see what percentage of glacial earthquakes from the testing set occur within regions predicted by the vulnerability map, in order to estimate its predictive power.   

  

~~ Machine Learning Prediction ~~   

  
*(2, optional) We want to examine which aspects of our ice sheet model are most important for determining where a glacial earthquake will occur. To do that, we will train a Random Forest algorithm on data from the maps of estimated ice velocity, basal thermal state, and surface melt in order to determine which attribute has the best predictive power for determining when glacial earthquakes occur.   



