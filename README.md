COMP257/ITEC657 Data Science Project
===

Group: Group E - Thursday 2PM 
Group Members: 
- Asim Adnan Eijaz 45565694
- Asma Asma 45766568
- Sonali Baliwada 45765707
- Siddhi Vilas Utekar 45814228



### Project Title: Predicting Forest Cover Types from Cartographic Variables
This Project experiments multiple techniques used for predicting forest cover type from cartographic variables.

===
The Project Notebook is written in Python 3, using the following libraries and packages:
- warnings
- datetime
- pandas
- seaborn
- numpy
- math
- scipy
- matplotlib
- sklearn

### Contents
* [Files](#Files)
* [Data Exploration](#Data Exploration)
* [Data Preperation](#Data Preperation)
* [Techniques and Methods](#Techniques and Methods)
* [Conclusion](#Conclusion)  


### Files
The data is from four wilderness areas located in the Roosevelt National Forest of northern Colorado USA.The cover type for each observation is from US Forest Service Information System (RIS) and the remaining Independent variables are from US Geological Survey (USGS) and USFS data.
The data file is in the project folder, named "Data".

===
The goals of the project were met in the following sequence:

### Data Exploration
The Notebook beging with exploratory data analysis on the cartographic variables. 
* Distribution of some Key Variables was observed.
* Descriptive analysis was carried out on the Dataset.
* Skewness of the variables was checked.
* Correlations between variables were plotted and analysed.
* Density violin plots were observed to check possible relationships between key variables target variables.
* Exploration of continuous and binary variabls, to see if we could possibly remove the variables that are not contributing to the data.  

### Data Preperation
* The dataset was resampled and balanced to equally split into training and tesing data.
* RFE Feature selection was carried out on the balanced data.

### Techniques and Methods
The goal of building a predictive model that classifies forest cover type, considering all the cartographic variables was achieved using the following techniques:
* Baseline Logistic Regression model tested on the balanced test and train data as well as selected features.
* Naive bayes model tested on the balanced test and train data as well as selected features.
* KNN tested on the balanced test and train data as well as selected features.
* Nueral Network built on the balanced test and train data as well as selected features.

### Conclusion
The best predictive model is Neural Network giving a 71.9% accuracy on test data, second best model is KNN with k =2. All the models mentioned above always gave a lower accuracy for selected features compared to using all features. Some other feature selection tenchinque could be applied to get a better outcome.

