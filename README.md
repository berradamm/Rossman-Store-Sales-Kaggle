

# Rossman Store Sales Kaggle
This project contains two notebook. The first one deals with data exploration, thus there is a lot of visualization that illustrate the influences of different variables.

The second one is the building of the model which implies Feature engineering , dataset cleaning and filling and finally the prediction with the redirection to a csv file for submission 
# Feature Engeeniring

![image](https://user-images.githubusercontent.com/45148200/50256410-7fa70080-03f6-11e9-8ed2-8f1efece1f88.png)

Here are presented the basics for datamining or wrangling using Python and Pandas.
## Clean the dataset
Here we are using pandas, thus, in order to clean our dataset we are going be to using some elementary strategies.
Depending on the amount of missing datas we either :

- Fill them following a chosen method such as the median or the mean when it comes to quantitatives datas
- Fill them following the previous or next value or by linear interpolation, polynomial or spline smoothing if we are dealing with time series data.
- Drop them if they are a few and form a group

Below i show you the way to better handlings for missing datas
### Missing data imputation
In the notebook shared the methods for exploring the dataset are not exhaustive.
Here is a paper with a large amount of technics and strategies aiming to fill the missing data the best way possible.
[Imputation of missing data](http://wikistat.fr/pdf/st-m-app-idm.pdf)

## Visualization
We are starting with the basic histograms and boxplot after droping the missing data.
Then we added a more elaborate tool which is Bivariate description

![image](https://user-images.githubusercontent.com/45148200/50256659-96018c00-03f7-11e9-9a3f-2219e29536cd.png)
## Results after the forecast
![prediction2](https://user-images.githubusercontent.com/45148200/50366230-c886c280-0578-11e9-8d4d-b7bf971506dd.png)
![prediction](https://user-images.githubusercontent.com/45148200/50366235-cb81b300-0578-11e9-9245-bf17ae2016e0.png)
## Kaggle Score 
- Public: 0.12886
- Private: 0.14032
