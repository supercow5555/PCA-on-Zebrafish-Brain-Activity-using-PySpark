# Principal Component Analysis (PCA) on Zebrafish Brain Activity using PySpark

## Overview

This project explores the use of Principal Component Analysis (PCA) to analyze brain activity data from larval zebrafish, utilizing PySpark for distributed computing. The dataset comprises light-sheet imaging recordings provided by the [Ahrens Lab](http://www.janelia.org/lab/ahrens-lab) at Janelia Research Campus.

## Dataset

The data captures the neural activity of a larval [zebrafish](http://en.wikipedia.org/wiki/Zebrafish) under various visual stimuli, recorded using light-sheet microscopy. The transparency of the zebrafish allows for comprehensive brain activity recordings. More details on the dataset and its collection methods can be found in the article ["Mapping brain activity at scale with cluster computing"](https://www.nature.com/articles/nmeth.3041).

## Contents

This notebook is divided into three main sections:

1. **PCA on Sample Data**
    - Steps of PCA on a sample dataset
    - Visualization of two-dimensional Gaussian distributions

2. **PCA Function and Evaluation**
    - Writing a custom PCA function
    - Evaluating PCA on various sample datasets
    - Visualizations of PCA projections in 2D and 3D

3. **Neuroscience Data Analysis**
    - Parsing, inspecting, and preprocessing neuroscience data
    - Performing PCA on the processed data
    - Visualizations including pixel intensity and normalized variance

## Visualizations

The notebook includes several visualizations to illustrate PCA and its application to the dataset:

1. **Two-dimensional Gaussians**: Visual representation of 2D Gaussian distributions.
2. **PCA Projection**: Visualization of data projected onto principal components.
3. **Three-dimensional Data**: Visualizations of data in 3D space.
4. **2D Representation of 3D Data**: Visualizing 3D data in a 2D plane.
5. **Pixel Intensity**: Visualization of pixel intensity in neuroscience data.
6. **Normalized Variance**: Plot showing the normalized variance explained by principal components.

## Code Highlights

- **PCA Implementation**: Custom PCA function implemented in Python.
- **Data Generation**: Functions to create random data from Gaussian distributions.
- **Visualization Functions**: Helper functions to prepare plots and visualize data.

## Usage

1. **Environment Setup**: Ensure you have PySpark and the necessary Python libraries installed.
2. **Data Preprocessing**: Follow the steps in the notebook to preprocess the neuroscience data.
3. **PCA Execution**: Run the PCA function and visualize the results.

## Requirements

- Python 3.x
- PySpark
- numpy
- matplotlib
- pandas


## Conclusion

This project demonstrates the application of PCA on neuroscience data using PySpark, highlighting the importance of exploratory data analysis and feature-based aggregation in understanding complex biological data.

## Acknowledgements

- Ahrens Lab at Janelia Research Campus for providing the dataset.
- [Nature Methods](https://www.nature.com/nmeth/) for the reference article.

