---
author: "Shixin Li"
date: "07/05/2021"
---

![](file/head_pic.png)

## Introduction

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
Five times more deadly than the flu, COVID-19 causes significant morbidity and mortality. COVID-19 looks very similar to other viral and bacterial pneumonias on chest radiographs, which makes it difficult to diagnose. It can be diagnosed via polymerase chain reaction to detect genetic material from the virus or chest radiograph. However, it can take a few hours and sometimes days before the molecular test results are back. By contrast, chest radiographs can be obtained in minutes. We want to help radiologists diagnose millions of COVID-19 patients more confidently and quickly using the chest radiographs. This will also enable doctors to see the extent of the disease and help them make decisions regarding treatment. Therefore, we are trying to develop a computer vision model to identify and localize COVID-19 abnormalities in an efficient and quick way. 

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[For More Information, click here.](https://www.kaggle.com/c/siim-covid19-detection)


## Project Organization

##### file: 
* Project Proposal 
* head_pic.png

##### NoteBooks:
* covid19_detection_datawrangling_eda.ipynb: learning the data information and cleaning the image data
* pre_processing&Modeling.ipynb: image data preprecessing, buliding and training image classification models

##### reports:
* ISIIM-FISABIO-RSNA COVID-19 Detection.pdf: ppt report of this project in pdf format
* SIIM-FISABIO-RSNA COVID-19 Detection.pptx : ppt report of this project
* Vgg16Info.txt : information of the final model
* SIIM-FISABIO-RSNA COVID-19 Detection report.pdf: the report about this project in detail

#### Data:
* train_image_level.csv.zip: the original study level dataframe form the offical website 
* train_study_level.csv: the original image level dataframe form the offical website 
* rescaled_image_info.csv: image information after rescaling the and changing the dcm format to png

Note: since the image data set is too big, I did not upload it. You can find it in the official website.


