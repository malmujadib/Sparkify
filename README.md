# Sparkify


### Introduction:

This project is the analysis of a dataset that contains user logs for a music streaming service called Sparkify which emulates a real streaming service like Spotify & Pandora.The Sparkify music services looks to identify the population of users that churn (they can be users from the free service, or the paid service). Once the possible criteria for churn are better undestood, our objective is to build a model and predict the users churn so that some specific attention can be given to the users and try to retain them on the platform.My Blog [here](https://medium.com/@mohdfaiz1415/how-to-predict-customer-churn-using-apache-spark-11874e9f22fc)


### Libraries used:

* pandas
* seaborn
* matplotlib
* pyspark


### Results:

After running the best model on the validation data, we managed to achieve an accuracy of 79.2%. This results is quite good, based on the small size of our dataset,
and the relative small portion of churn users in the dataset. That latter point is also the reason why we optimised the model on the F1 metric, as otherwise a dumb
model which would only output zero as a prediction would still be able to get a high accuracy even though it would not generate any real positive, but would 
generate a lot of false negatives instead. In theory this dumb classifier would get a 77.3% on the validation set. The successful model is the Multilayer Perceptron 
classifier. 


### Acknowledgements:

I would like to thank  Udacity for the unique big data experience.
