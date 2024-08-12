# Crop_Production_Analysis_in_India
**Problem Description :**

* The collection includes thorough statistics on India's crop production, broken down by state and district. The dataset spans the years 1997 to 2023 and includes data for the four principal crop seasons of kharif, rabbi, summer, and fall. The report offers details on the annual yield and production of crops farmed around the nation.
* Experts and farmers who are interested in understanding agricultural production patterns in various regions of India will find the dataset to be helpful. You can decide how to increase agricultural productivity in the nation by examining the data and figuring out the variables that affect crop yields and production.
* Since it is raw data, researchers can only study it however, it is possible to utilise the dataset to train machine learning models that can forecast crop yields and production in various regions of the nation.
* This information can be useful for agricultural enterprises and organisations. The dataset offers a thorough overview of crop production statistics in India, which is crucial for comprehending the nation's agricultural environment and creating successful sustainable agriculture plans.

**Exploratory Data Analysis(EDA) and Data Cleaning :**

**Data Cleaning :-** Data looks to be fine, there is no cleaning required

**Exploratory Data Analysis :-** Several significant conclusions drawn from the analysis 

**Model Building :**

* As there are more values in the category columns, label encoding may be a frequently employed technique since target directed encoding is used to establish some sort of relationship with the target variable.
* Because it requires awhile to individually do each categorical encoding, replace a missing value, and normalise with a standard scalar, scikit learn pipeline is employed.
* A separate pipeline is created for categorical and numerical data, and these pipelines are combined with ColumnTransformer before the ML model is put to the pipeline. The dataset is divided into train and test phases.

