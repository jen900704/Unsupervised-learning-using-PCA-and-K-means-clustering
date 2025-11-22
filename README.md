# Unsupervised Learning Using PCA and K Means Clustering

This project applies unsupervised learning techniques to explore the structure of a dataset using Principal Component Analysis and K Means clustering. The goal is to identify meaningful patterns without relying on labeled examples.

## Overview

The analysis begins with an examination of the raw dataset, including basic visualization of the original features. Principal Component Analysis is then used to reduce dimensionality and create a lower dimensional representation that captures the main variance in the data. After dimensionality reduction, K Means clustering is applied to group data points into distinct clusters based on similarity in the transformed feature space.

## Repository structure

data  
Contains the input dataset used in the analysis.

notebooks  
Contains the complete notebook used to perform the analysis.

reports  
Contains the project report summarizing the methodology and results.

## Methods

The dataset is first explored with simple visualizations, including histograms and bar plots of individual features.  
Principal Component Analysis is applied to reduce the dataset to two principal components, as shown in the scatter plot of the transformed data.  
K Means clustering is then applied to the PCA result, producing a set of clusters that reflect hidden patterns within the dataset.

## Results

The PCA scatter plot shows how the data can be represented in a two dimensional space while preserving major variance in the features.  
The clustering visualization demonstrates that K Means successfully separates the data into meaningful groups within the PCA space.  
These findings illustrate how dimensionality reduction and clustering can be combined to reveal structure that may not be obvious in the original feature space.

## Notes

All code used in the analysis is included in the notebook.  
The report provides a concise summary of the workflow, visualizations, and conclusions.

## Author

Hsiang Chen Yeh
