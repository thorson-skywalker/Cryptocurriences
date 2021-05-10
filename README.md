# Cryptocurriences

## Purpose

The purpose of this project was to use unsupervised machine learning to break down cryptocurrencies into groupings that can be analyzed for investment opportunities.

## Overview

We gathered data on current cyptocurrencies from "CryptoCompare" and cleaned it using Pandas in python. After cleaning the data we reduced the dimensions using PCA from sklearn and used a KMeans model to separate that data into classes based on the new dimensions. After breaking down the data we used hvplot to display the data using three different methods. The first we displayed the data using a 3D scatter plot. The second, we displayed information regarding currently trading cryptocurrencies onto a table. Thridly, we used MinMax scaler to scale the Total Coins Mined and the Total Coin Supply and then used that information to group them into classes. With this information we plotted a scatter graph to show groups and their outliers.