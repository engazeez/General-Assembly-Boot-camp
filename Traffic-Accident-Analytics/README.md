# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Local Traffic, Statistical Summaries and Inference

### Overview
This was the first project I worked in data science journey. I applied essentials skills that I learnt last weeks, I covered the following:
-basic statistics (distributions, confidence intervals, hypothesis testing)
- many Python programming concepts
- programmatically interacting with files and directories
- visualizations
- EDA
- working with Jupyter notebooks for development and reporting 

Through this project I  toke a look at the number of traffic accidents and driving licenses issued in Saudi Arabia. I identified trends in the data and created some graphs to see the big picture from each features in the data as well as data analysis methods importing, cleaning and looking for some statistics to recognize details more about data. 


### Datasets

#### Provided Data

For this project, you'll have two provided datasets:

- [Traffic Accidents and Casualties by Region](https://git.generalassemb.ly/DSI-MISK-VIII/Project-1/blob/master/data/saudi-arabia-traffic-accidents-2008.csv)
- [Driving Licenses Issued By Administrative Area](https://git.generalassemb.ly/DSI-MISK-VIII/Project-1/blob/master/data/saudi-arabia-driving-licenses-2004-2008.csv)

You can see the source for the accident data [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/), and the source for the license data [here](https://datasource.kapsarc.org/explore/dataset/saudi-arabia-traffic-accidents-and-casualties-injured-dead-2008/).

#### Additional Data

the website of the General Department of Traffic [here](https://www.moi.gov.sa/wps/portal/Home/sectors/publicsecurity/traffic/!ut/p/z1/04_iUlDg4tKPAFJABjKBwtGPykssy0xPLMnMz0vM0Y_Qj4wyizfwNDHxMDQx8nZ3CTQ1cAz0dvX3dDE2MnA00vfSj8KvIDg1T78gO1ARAHn-YJg!/) for further investigation into policies and other data that may be of interest.


####  data dictionary

Here all features of each dataset 

|Feature|Type|Dataset|Description|
|---|---|---|---|
|year|int|Traffic_Accidents|Accident occuring year|
|region|object|Traffic_Accidents|Accident occuring region|
|casualty_status|object|Traffic_Accidents|casualties_status {Casualties - Injured, Casualties - Dead, Accidents }|
|casualties_total|int|Traffic_Accidents|casualties total per year|
|x|float|Traffic_Accidents|Latitude of region coordinate|
|y|float|Traffic_Accidents|Longitude of region coordinate|
|year|int|Driving_Licenses|Driving License issuance year|
|region|object|Driving_Licenses|Driving License issuance region|
|driving_license_total|int|Driving_Licenses|Driving licenses issuance total per year|
|x|float|Driving_Licenses|Latitude of region coordinate|
|y|float|Driving_Licenses|Longitude of region coordinate|



#### Steps

- Data Import and Cleaning
- Exploratory Data Analysis
- Visualize the data
- Descriptive and Inferential Statistics
- Conclusions and Recommendations 
