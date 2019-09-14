Data Science Project Proposal
===

Group Members
---
* Asim Adnan Eijaz 45565694
* Asma Mir
* Sonali 45765707
* Siddhi

### Title: Predicting Forest Cover Types from Cartographic Variables
Natural resource manager have the duty of developing ecosystem management strategies, for this they require basic descriptive information of forested lands to create better strategies. Generally these managers don't have access to data of lands next to their own jurisdiction. One way this could be extracted is through predictive modelling.
In this Project multiple techniques will be used in predicting forest cover type from cartographic variables. The data is from four wilderness areas located in the Roosevelt National Forest of northern Colorado USA.
The cover type for each observation, which is a 30 x 30 meter cell, is from US Forest Service Information System (RIS), Other Independent variables are from US Geological Survey (USGS) and USFS data. The data is in raw format with binary columns of data for qualitative variables for wilderness areas and soil types.


### Goals
The main goal of this project will be to build a predictive model that can classify forest cover type based on all cartographic variables. There are 6 possible forest cover types.
* Correlation between the variables to explore any significant relationships or collinearity
* Analyse Distance variables
* Analyse Soil types
* Analyse Elevation type
* Create a baseline Liner Regression Model
* Feature extractions
* Linear Model with extracted Features
* Build a Naive Bayes Model with extracted feature
* Build a Neural Network with Extracted features

### Dataset description
The data used in this project is a forest cover-type dataset. It is obtained from the UCI Machine Learning Repository. The dataset contains 581012 observations in total which consists of 54 variables and 6 outcome variables. The data is in raw format and contains binary (0 or 1) columns for the qualitative independent variables.

The 54 variables (including their datatypes) are:
* Elevation (Quantitative)
* Aspect (Quantitative)
* Slope (Quantitative)
* Horizontal_Distance_To_Hydrology (Quantitative)
* Vertical_Distance_To_Hydrology (Quantitative)
* Horizontal_Distance_To_Roadways (Quantitative)
* Hillshade_9am (Quantitative)
* Hillshade_Noon (Quantitative)
* Hillshade_3pm (Quantitative)
* Horizontal_Distance_To_Fire_Points (Quantitative)
* Wilderness_Area - 4 binary columns (Qualitative)
* Soil_Type - 40 binary columns (Qualitative)

The 6 outcome variables are the cover types (cover_type): 
* Type 1 - Spruce/fir (Integer - 1)
* Type 2- Lodgepole pine (Integer -2)
* Type 3-  Ponderosa pine (Integer -3)
* Type 4- Cottonwood/willow (Integer -4)
* Type 5- Spruce/fir and aspen (Integer -5)
* Type 6- Douglas-fir (Integer -6)

This data is based on the Roosevelt National Forest of Northern Colorado's  wilderness areas.
The raw data needs to cleaned by removing/imputing outliers and missing values. Each variable is explored and it's distribution is checked.