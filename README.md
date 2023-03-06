# Rainfall_Prediction_18_days

The two pickle files contain the datasets concerning the 18 days of rainfall measurements described in the article "Rain Discrimination with Machine Learning Classifiers for Opportunistic Rain Detection System using Satellite Micro-wave Links". The data have been collected using sensors mounted on two parabolic dishes having a diameter of 60cm and 85cm, respectively.  

Open the datasets using the pickle library for python with the following commands:

*import pickle as pk*  

datasetPath = "Dataset_85cm.pkl"  
with open(datasetPath, "rb") as f:  
    dataset = pk.load(f)  
    f.close()  
   
The "dataset" variable is a dictionary containing the 18 days SRS measurements expressed in mV, the 18 days TBRG measurements expressed in mm/min, and the labels for each minute of observation (0 for no-rain, 1 for rain)

Please cite the article as:

Gianoglio, C.; Alyosef, A.; Colli, M.; Zani, S.; Caviglia, D.D. Rain Discrimination with Machine Learning Classifiers for Opportunistic Rain Detection System Using Satellite Micro-Wave Links. Sensors 2023, 23, 1202. https://doi.org/10.3390/s23031202
