# Predicting_WaterlooHealthInspections
Exploring City of Waterloo's Open Data to predict the appropriate priority order for health inspections to find critical health infractions.

## Overview

The City of Waterloo is quickly growing, due in part, to new high-tech businesses within the KW core.  
As the population grows, new food establishments will be borne to meet increased demand. Although the current
size of the Public Health department may be able to inspect all the current premises in the City, this may no
longer be the case in the future as there will be more establishments than an inspector can handle in a given year.  
A food inspector's primary concern is critical violations which can lead to a break out of food borne
illnesses. Therefore, it is essentiall that inspectors have a prioritized list of premises to check.  
The faster a critical biolation is found, the less likely outcome of a food illness int he population or immediate customers
can occur.  
  
Thus, the primary goal of this data analysis is to design a model that, with a few atributes of a food establishment,  
can determine whether an inspection will yield a critical, non-critical, or no violations. Thereby, creating a priority queue
of premises to inspect.


## Steps

Markup : 1. Clean the datasets, and form a master set.
		 2. Split the master into training and testing data (with features and one target).
		 3. Train three different classifiers on the master.
			1. Logistic Regression
			2. Support Vector Machine (SVM)
			3. XGBoost
		 4. Use the best classifier to predict whether an inpection will have a critical violation or not.


## Dataset

Source data is from Public Health office of City of Waterloo. Made available through its Open Data initiative.  
Provides public data on geogrpahically-fixed premises and the result of their inspections within the City.  
Link to the data [here](http://www.regionofwaterloo.ca/en/regionalGovernment/FoodPremiseDataset.asp).


## Analysis
[TODO]


## Conclusions
[TODO]


## Possible Improvements
[TODO]


## Dependencies

* pandas  
* scikit-learn  
* xgboost  
* jupyter  

All dependencies are avaiable on pip or pip3. Jupyter is required to run this notebook (`jupyter notebook` in shell).







