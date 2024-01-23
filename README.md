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
![model_architecture](https://github.com/najmi-hisham/CAPSTONE1-YPAI07/assets/69621770/a6f8a8b9-ab4e-496d-b85b-e9bdd297b8ef)


# RESULT
1. EPOCH LOSS FOR TRAIN AND VALIDATION DATASET

![Tensorboard Loss](https://github.com/najmi-hisham/CAPSTONE1-YPAI07/assets/69621770/9261486c-4ea8-4a99-be2d-e6d84d0f98e8 "Tensorboard")

![Training Loss](https://github.com/najmi-hisham/CAPSTONE1-YPAI07/assets/69621770/0644470d-041a-4fcc-9935-45e85fbdc365  "Training Loss only")

2. REAL VS PREDICTED CASES

![Predicted vs Real](https://github.com/najmi-hisham/CAPSTONE1-YPAI07/assets/69621770/6162eef4-0202-4f81-87e3-fa6c1872542f)


# 

Credited to 'GitHub - MoH-Malaysia/covid19-public: Official data on the COVID-19 epidemic in Malaysia. Powered by CPRC, CPRC Hospital System, MKAK, and MySejahtera.'


#

