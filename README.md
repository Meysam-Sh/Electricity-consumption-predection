This is an impelemntation of NN Using Keras for electricity consumption prediction. The data were collected from ~12000 households selected at random using a complex multistage, area-probability sample design (https://www.eia.gov/consumption/residential/data/2009/index.php?view=microdata). The data cleaning part of the work inludes:

* encoding the categorial variables 
* removing variables if more than 95% of them are 0 or -2
* removing variables with a constant vaule
* Min-Max normalization
* replacing missing values of a feature with its mean  

**The r2-score achived by the model: 99%** 

--------------------------------
![loss](https://user-images.githubusercontent.com/62679750/122396657-98081f80-cf4e-11eb-826e-1d8d999b45aa.png)
![r2-score](https://user-images.githubusercontent.com/62679750/122396700-a48c7800-cf4e-11eb-97ab-c24dba5917bf.png)

