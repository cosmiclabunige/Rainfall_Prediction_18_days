# Rainfall_Prediction_18_days

The two pickle files contain the datasets concerning the 18 days of measurements described in the article "Rain Discrimination with Machine Learning Classifiers for Opportunistic Rain Detection System using Satellite Micro-wave Links". 

Open the datasets using the pickle library for python with the following commands:

import pickle as pk

datasetPath = "Dataset_85cm.pkl"__
with open(datasetPath, "rb") as f:__
    dataset = pk.load(f)__
    f.close()__
   
The "dataset" is a dictionary containing the 18 days SRS measurements expressed in mV, the 18 days TBRG measurements expressed in mm/min, and the labels for each minute of observation (0 for no-rain, 1 for rain)  
