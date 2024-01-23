# CAPSTONE1-YPAI07
This project implement LSTM or Long Short Term Memory model in neural network to apply it with time series data. This project use URL below as dataset to which contain COVID 19 data in MALAYSIA. To be specific, only column from cases_new and date
to create a prediction of the next day new cases.

URL = 'https://raw.githubusercontent.com/MoH-Malaysia/covid19-public/main/epidemic/cases_malaysia.csv'.

# File content
1. time_series_helper.py
2. Najmi_Assesment1.py
3. Result

The main file is from the second content. This python file consist of all step to build LSTM model to deal with time series data. Tensorboard being implemented to analyze live training performance (epoch loss and mean absolute percentage error). 
For the time_series_helper, it was python class that adjust the window size for this project (30 days as input, next 30 days as label). The summary for this model architecture can be seen as below.

# MODEL ARCHITECTURE
![image](https://github.com/najmi-hisham/CAPSTONE1-YPAI07/assets/69621770/21f7853a-a3b6-4634-ae9d-1cdf2b04136b)

# RESULT
1. EPOCH LOSS FOR TRAIN AND TEST DATASET

![EPOCH_LOSS_train test](https://github.com/najmi-hisham/CAPSTONE1-YPAI07/assets/69621770/75717d57-ca68-4147-88a7-aaf94eff555d)

2. MEAN ABSOLUTE PERCENTAGE ERROR TEST DATASET

![MAPE_test](https://github.com/najmi-hisham/CAPSTONE1-YPAI07/assets/69621770/f45bb1c3-2fda-4ff9-a93f-dc69a275b1c5)

3. REAL VS PREDICTED CASES

![predicted vs real](https://github.com/najmi-hisham/CAPSTONE1-YPAI07/assets/69621770/71d22858-292c-4c98-a32e-94799654d005)


# 

Credited to 'GitHub - MoH-Malaysia/covid19-public: Official data on the COVID-19 epidemic in Malaysia. Powered by CPRC, CPRC Hospital System, MKAK, and MySejahtera.'


#

