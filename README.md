# Project Uber Pickups

This project is based on Non-Supervised Machine Learning model. 
The goal was to create some clusters in New-City to determine where a Uber driver could find the maximum number of customers according to the choosen date and hour.


## A 2-step project

### Step 1
There are several methods for clustering in machine learning. I had to test them before creating anything because some methods could be better than others according to dataset.

In step 1, I tested two methods to create clusters:
 - KMeans
 - DBSCAN

Then I associated for each method two ways to calculate the best number of clusters:
- elbow method
- silhouette method

### Step 2
After finding the best model with the best method to calculate the number of clusters, I created a second notebook where the driver could choose a date and several hours then see on GMap where he must driver to find customers.

I decided to train the model each time the driver choose a day because the dataset could be changed in future version.


## Improvement
Adding some other months will be the best improvement in order to have a complete year.
Even better, with the good API, this application could have data in real time.

Deployment with Flask would be the last step of the project