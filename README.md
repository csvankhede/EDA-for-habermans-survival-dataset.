# EDA for habermans survival dataset.
![medical-web-designs](https://user-images.githubusercontent.com/25454660/62775707-0dd71080-bac6-11e9-9d5e-bfdbe429aaa1.jpg)

Exploratory data analysis for habermans survival dataset

This notebook contain different data analysis and visulization technique applied on habermans survival dataset.
Which include 
* 2D Scatter plot
* Pair plot
* Univarint Analysis
* PDF(Probability Density Function)
* CDF(Commulative Distibution Function)
* Box-plot
![image](https://user-images.githubusercontent.com/25454660/62775865-90f86680-bac6-11e9-8bd0-4a289f8aea60.png)
* Violin-plot
* Contour plot. 

Here in the given dataset attribute information is as given below:

* Age: Age of patient at time of operation (numerical)
* Op_Year: Patient's year of operation (year - 1900, numerical)
* axil_nodes: Number of positive axillary nodes detected (numerical)
* Surv_status: Survival status (class attribute)

  1 = the patient survived 5 years or longer
  
  2 = the patient died within 5 year

It also include Percentiles, Quartiles, IQR(Interquartile Range), MAD(Mean Absolute Deviation).
Dataset was taken from https://www.kaggle.com/gilsousa/habermans-survival-data-set

## Used packages:
* pandas
* seaborn
* matplotlib
* numpy
* statsmodels

Above packages can be installed using pip.

`pip install [package_name]`
