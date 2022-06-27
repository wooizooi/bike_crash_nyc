Bicycles Accidents in NYC
Use LR/KNN/Decision Tree/Random Forest classification algorithms from sklearn to predict the accident location. I will only select a few features I believe are more relevant to accident location. Categorical data will be treated with Pandas get_dummies method. Rows with missing values will be dropped.

Scenario and Data: NYC is known for its traffic jams. So, going around on a bike is a big time saver. But there’s some risk of having an accident. We have two datasets to do some research on them:

Bike Stations: https://feeds.citibikenyc.com/stations/stations.json

Vehicle crashes: https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-CollisionsCrashes/h9gi-nx95

To load the data into the jupyter notebook run the code in Step 2 (# import from url). Alternatively: Download the data to your local device and load the data from there using the code in Step 2 (# import from device).
After loading the datasets run the code step by step.

Questions:

What is the most dangerous NYC borough / area for a bicycle rider? Use visualization.

What would you change in the locations of bike stations to increase safety? Use visualization.

Where can an accident occur and how close is this from the nearest bike station? Create a predictive model.
