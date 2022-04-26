# CMSE202_Project

'''We found a data set with exoplanet and non-exoplanet fluxes we then researched how we would need to read in and edit
the data. So we found SMOTE which would allow us to be able to create new data so that our exoplanets. We also split
data into a test and a train data set so that can train our machine learning. We then plotted the data so that we can
observe the intensity of the light fluxes of the training sets. We plotted the exoplanet light fluxes first. We then 
also plotted the non-exoplanet light fluxes. We can see that in the plot of the light fluxes that there isn't that 
same wave pattern of the fluxes that the exoplanets had. We then also plotted the light fluxes of FLUX.1 so that we
could find an outlier. We then dropped the data point that was an outlier. We then split up our data into training fluxes
and training labels and test fluxes and test labels we also then normalized the data so that the data would be smoother
and we applied the Gaussian filter so that our data would be smoother. We then used different methods to find the best
machine learning model. We compared K Closest Neighbor, Logistic Regression, Decision Tree Classifier, and Perceptron. We then used SMOTE to create new data so that our data would be more balanced. We found that when using SMOTE 
that the best model is K Closest Neighbor and without SMOTE we found that Logistic Regression was the best. 

In the project, Nathan researched and created the different models of K Closest Neighbor, Logistic Regression,
Perceptron, and Decision Tree. Nathan also found and understood when producing the graphs that the area under the curve
(AUC). He then also created the classification reports for each of the models that we used. Nathan also created the
models when we are using SMOTE that would allow us to see when our data is then more balanced and we can see what the
best model is for our data. Nathan also helped to add some of the images to the powerpoint and also described the results in the images in the powerpoint

In the project, Dustin researched SMOTE to create a way of creating new data because our data was skewed towards 
many points not being exoplanets. And he also created the box plot and researched the best way to get rid of outliers
in the data set so that our models are more accurate in predicting whether a light flux is an exoplanet or not. Dustin
also created a different plot of the light fluxes of the exoplanets and the plot of the non-exoplanets. Dustin also 
helped in adding to the powerpoint by adding descriptions of the different computational techniques we used in the coding he also helped to add transitions to the powerpoint and make the powerpoint more visually appealing

In the project, Ethan researched and found an interquartile range (IQR). He did this so that we could identify and 
get rid of the outliers so that our data can get better when we run our models. His IQR code and research were eventually not used because we found that when we ran the data after removing the outliers the method would get rid of some of the very few exoplanets in our datasets. He also created and edited the powerpoint. He added in a good amount of the result images and explained the results that we got from the images. He also added the transitions in between the slides for our Powerpoint. He also wrote this readme file.

In the project, Nolan found a second data set and he worked on it to create a machine learning model for it and used the SVM model and he got results for predicting exoplanets using the data provided in the dataset. We later decided not to use this second dataset to keep our project concise and understandable to the audience. The dataset had a different set of features that might make it confusing to explain to the audience. This also may have made it difficult to compare to our other dataset.'''


```python

Sources

'https://www.kaggle.com/datasets/keplersmachines/kepler-labelled-time-series-data?select=exoTest.csv'

"https://github.com/nageshsinghc4/Exoplanet-exploration/blob/master/exoplanet-exploration-using-ml.ipynb"

'https://exoplanetarchive.ipac.caltech.edu/cgi-bin/TblView/nph-tblView?app=ExoTbls&config=TOI'
```
