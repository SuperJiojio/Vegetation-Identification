# Vegetation-Identification

Wanqiu Xiong,Jiao Zhao,Peijing Zheng

## Abstract
Use Random Forest Classifier from the scikit-learn library to create a training model based on the satellite imge data of Salzburg from 2018 to 2022. And use that model forecast the vegetation and non-vegetation area of Salzburg in 2023.

## Concrete steps:

Collect satellite data and transfer it to labeled data
Extract the bands of vegetation and non-vegetation(.txt file)
Model training: import Random Forest Classifier from the scikit-learn library to train.
Model forecast: use the trained model to forecast the vegetation of Salzburg city.
Automate Mask Generator:use Segment Anything library to visualize the forecast results.  

## Packages:

GDAL library 

The Scikit-learn library(Random Forest Classifier)


## Expected result:

The vector file of the forecast of vegetation and non-vegetation area of Salzburg in 2023.

## Group division:

Wanqiu Xiong: data pre-processing and feature extraction

Peijing Zheng: random forest model

Jiao Zhao:Use rfm to forecast  

## Schedule and time:

Due in the mid of August(15.08.2023)

The worktime of each person:around 70 hours including looking for relevant information, writing codes and debug. 

