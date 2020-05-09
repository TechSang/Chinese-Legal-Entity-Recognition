# Chinese-Legal-Entity-Recognition  
![](https://img.shields.io/badge/CNSCC-300-lightgrey)  ![](https://img.shields.io/badge/license-Apache--2.0-blue) ![](https://img.shields.io/badge/version-1.2.1-yellow)
## Introduction
With the development of artificial intelligence, many industries, such as intelligent legal service, has also ushered in a new round of technological changes. Although lots of international research have been done in this field, the disparity of social attention in law-related tasks between China and the west, as well as the differences in language families, make it is still in its infancy in China. To solve the problems of low accuracy and unsatisfactory output of traditional methods, this paper aims to design a Chinese legal entity extraction system based on the pre-trained model.

## Dataset  
中国‘法研杯’法律智能挑战赛（任务：罪名预测、法条推荐、刑期预测）的数据. ([CAIL2018](http://cail.cipsc.org.cn/))

## Structure
The process of the project can be divided into three parts – data processing, data labelling and model building.  
![Flow Chart](https://github.com/TechSang/Chinese-Legal-Entity-Recognition/blob/master/Figure/Flow%20chart.png)  
* Data processing section 
Dataset cleaning and format, legal item extraction and complement.  
![Flow Chart](https://github.com/TechSang/Chinese-Legal-Entity-Recognition/blob/master/Figure/Data%20Processing.png)  
* Traverse Comparsion and Word Similarity Comparsion of tagging the entities.   
![Flow Chart](https://github.com/TechSang/Chinese-Legal-Entity-Recognition/blob/master/Figure/Data%20Labeling.png)    
* Model building section includes Bi-LSTM CRF, convolutional network based and pretrained model based model.   
![Flow Chart](https://github.com/TechSang/Chinese-Legal-Entity-Recognition/blob/master/Figure/Model%20Building.png)  

