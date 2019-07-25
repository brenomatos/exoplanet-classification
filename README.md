# Exoplanet Classification
In this repository we compare multiple machine learning algorithms for binary classification.

The methods will be tested on the task of binary classification of exoplanet candidates found by NASA’s Kepler spacecraft, found [here](https://exoplanetarchive.ipac.caltech.edu).

An exoplanet is a planet outside of the solar system (i.e. does not orbit
the sun). The spacecraft first identifies possible signs of exoplanets, referred to as Kepler Object
of Interest (KOI). Not all KOIs are actual exoplanets however, some are false positives of different
natures. The task performed is to classify KOIs between confirmed exoplanets and false positives. Each
observation corresponds to a KOI and the features are estimates of the physical properties of the
(possible) exoplanet (radius, temperature, features of the host star, etc).

# Algorithms
We'll compare the following machine learning algorithms:
1. Naive Bayes
2. Decision Tree
3. SVM
4. K-NN
5. Random Forest
6. Gradient Tree Boosting

# Graphs
In this repository, we create multiple graphs. Here are some examples of those graphs:

For each model, we create a line graph to represent the variation of theaccuracy score while we variate the algorithms parameters:
![Line Graph](/graphs/linegraph.png "Line Graph")

For the SVM algorithm, we vary the kernels, so we use a bar graph to represent this model's accuracy"
![Bar Graph](/graphs/bargraph.png "Bar Graph")


We also compare all models regarding recall, precision, train/test accuracy:
![Comparative Graph](/graphs/comparative.png "Comparative Graph")



Also, for every model created, we plot a ROC curve
![ROC Graph](/graphs/linegraph.png "ROC Graph")



# Built With
[Scikit Learn](https://scikit-learn.org/stable/)
[Pandas](https://pandas.pydata.org/)
[Seaborn](https://seaborn.pydata.org/)
