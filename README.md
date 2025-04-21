**UFO Sightings Analysis**

This repository contains a Jupyter Notebook analyzing UFO sighting data using clustering and linear regression techniques.

**Overview**

The notebook performs the following analysis:

-Loads and cleans UFO sighting location data (latitude/longitude)

-Applies K-means clustering to identify geographic patterns

-Creates separate linear regression models for each cluster

-Visualizes the results with geographic clusters, regression lines, and major city markers

**Key Features**

-Data cleaning and preprocessing

-K-means clustering (k=2) of sighting locations

-Linear regression analysis per cluster

-Geographic visualization using matplotlib

-Markers for major cities (Beijing, London, New York, Dakota)

**Requirements**

-Python 3

-pandas

-numpy

-scikit-learn

-matplotlib

**Usage**

-Clone the repository

-Install required packages: pip install pandas numpy scikit-learn matplotlib

-Open and run the Jupyter Notebook UFO_sighting.ipynb

**Data**

The notebook expects a CSV file named ufo_sighting.csv with columns for latitude and longitude. The sample data contains geographic coordinates of UFO sightings.

**Results**

The analysis produces a visualization showing:

-Geographic distribution of sightings

-Two distinct clusters (blue and green)

-Regression lines for each cluster

-Major city markers for reference

**Future Work**

Try different clustering algorithms or cluster counts

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement". Don't forget to give the project a star! Thanks again!
