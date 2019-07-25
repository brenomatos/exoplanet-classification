# Exoplanet Classification
In this repository we compare multiple machine learning algorithms for binary classification.

The methods will be tested on the task of binary classification of exoplanet candidates found by NASA’s Kepler spacecraft, found [here](https://exoplanetarchive.ipac.caltech.edu).

An exoplanet is a planet outside of the solar system (i.e. does not orbit
the sun). The spacecraft first identifies possible signs of exoplanets, referred to as Kepler Object
of Interest (KOI). Not all KOIs are actual exoplanets however, some are false positives of different
natures. The task performed is to classify KOIs between confirmed exoplanets and false positives. Each
observation corresponds to a KOI and the features are estimates of the physical properties of the
(possible) exoplanet (radius, temperature, features of the host star, etc).
