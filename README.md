# CMSE202_Project

```python

'''we found a data set with exoplanet and non exoplanet fluxes we then researched how we would need to read in a edit
the data. So we found SMOTE which would allow us to be able to creat new data so that our exoplanets. We also split
data into a test and a train data set so that can train our machine learning. We then plotted the data so that we can
observe the intensity of the light fluxes of the training sets. We plotted the exoplanet light fluxes first. We then 
also plotted the non exoplanet light fluxes. We can see that in the plot of the light fluxes that there isnt that 
same wave pattern of the fluxes that the exoplanets had. We then also plotted the light fluxes of FLUX.1 so that we
could find an outlier. We then dropped the data point the was an outlier. We then split up our dat into a train fluxes
and train labels and test fluxes and test labels we also then normalized the data so that the data would be smoother
and we applied teh Gaussian filter so that our data would be smoother. We then used different methods to find the best
mschine learning model. We compared K Closest Neighbor, Logistic Regression, Decison Tree Classifier and Perceptron. We then used SMOTE to create new data so that our data would be more balanced. We found the that when using SMOTE 
that the best model is K Closest Neighbor and without SMOTE we found that Logistic Regression was the best. 

In the project Nathan researched and created the different models of K Closetst Neighbor, Logistic Regression,
Perceptron, and Decison Tree. Nathan also found and understood when producing the graphs that the area under the curve
(AUC). He then also created the classification reports for each of the models that we used. Nathan also created the
models when we are using SMOTE that would allow us to see when our data is then more balances and we cna see what the
best model is for our data. Nathan also helped to add some of the images to the powerpoint and also described the results in the images in the powerpoint

In the project Dustin researched SMOTE to create a way of creating new data becasue our data was skewed towards 
many points not being exoplanets. And he also created teh box plot and researched teh best way to get rid of outliers
in the data set so that our models are more accurate in predicting weather a ligh flux is an exoplanet or not. Dustin
also created the differnet plot of the light fluxes of the exoplanets and the plot of the non exoplanets. Dustin also 
helped in adding to teh powerpoint by adding descritions of the different computational techniques we used in the coding he also helped to add transistions to the powerpoint and make teh powerpoint more visually appealing

In the project Ethan researched and found interquartile range (IQR). He did this so that we could identify and 
get rid of the outliers so that our data can get better when we run our models. my IQR code and research was eventually not used becasue we found that when we ran the data after removing the outliers that the method would get rid of some of our very few exoplanets in our datasets. I also created and edited the powerpoint. I added in a good amount of the result images and explained the results that we got from teh images. I also added the transistions in between the slides for our Powerpoint. I also wrote the readme file

In the Project Nolan found a second data set and he worked on it to create a machine learning for it and used the SVM model and he got resulst for predicting exoplanets'''


```python

Sources

'https://www.kaggle.com/datasets/keplersmachines/kepler-labelled-time-series-data?select=exoTest.csv'

"https://github.com/nageshsinghc4/Exoplanet-exploration/blob/master/exoplanet-exploration-using-ml.ipynb"
```
