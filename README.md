# Unsupervised learning
Use unsupervised learning tecniques to learn from image data.


## Overview
The goal is to use clustering algorithms to learn about image data.

The data used are the famous images from the Olivetti faces dataset. Even though all the images in the set are labelled, for the purpose of unsupervised learning, we are going to assume that no labels are provided.

The clustering algorithms used are K-Means and Gaussian Mixture.


All the steps are contained and documented in the Jupyter Notebok [Unsupervised learning](). There are 3 major steps:
- loading the data
- use [PCA](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html) to reduce dimensionality
- train the clustering algorithms


### Clustering algorithms
The unsupervised learning tasks used are:
- [K-Means](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
- [Gaussian Mixture](http://scikit-learn.org/stable/modules/generated/sklearn.mixture.GaussianMixture.html)


### Dataset
The data used is the classic [Olivetti faces dataset](https://scikit-learn.org/0.19/datasets/olivetti_faces.html#olivetti-faces). The dataset contains 400 grayscale 64 x 64-pixel images of 40 people (10 images each).



___

## How to start
1. Check out that you have a working Python installation, preferably Python 3
2. Git clone the [repo][add link] and cd inside directory
3. Install requirements: 

    `pip install -r requirements.txt`
4. Use the jupyter notebook [Unsupervised](https://github.com/ElisaCovato/Spam-Classifier/blob/main/Spam%20classifier.ipynb) to download and familiarize yourself with the data, train, evaluate and fine tune the clustering algorithms
