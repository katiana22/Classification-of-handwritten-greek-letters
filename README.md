## Table of contents

* [General info](#general-info)
* [Dataset](#dataset)
* [Content](#content)
* [Application](#application)


## General info

This repository contains a python code used to perform classification tasks on a novel dataset of lowercase handwritten Greek letters.

## Dataset

The dataset can be found here: https://www.kaggle.com/katianakontolati/classification-of-handwritten-greek-letters

### Content

The dataset consists of 240 images of Greek letters (10 for each letter). The test dataset consists of 96 images (4 for each letter). We provide both the grayscale original high-resolution images in 2 zip files (train and test) and the low-resolution images (14x14 pixels) used for the classification in another 2 zip files (train and test). Finally, matrices that correspond to each low-resolution (14x14) image are given in 2 .csv files (train and test). Numbers in cells represent the grayscale intensities.

The last column in both .csv files contains the labels/ ground truth, that is the 24 different letters. Each letter corresponds to a number in a way that it is explained below:

Letter Symbols => Letter Labels
α=>1, β=>2, γ=>3, δ=>4, ε=>5, ζ=>6, η=>7, θ=>8, ι=>9, κ=>10,
λ=>11, μ=>12, ν=>13, ξ=>14, ο=>15, π=>16, ρ=>17, σ=>18, τ=>19, υ=>20,
φ=>21, χ=>22, ψ=>23, ω=>24

#### The original high-resolution images
(train _high _resolution.zip, test _high _resolution.zip)

#### The low-resolution (14x14) images
(train _letters _images.zip, test _letters _images.zip)

#### Training dataset
Grayscale intensities- with 240 rows/data, 196 columns/features, column 197 contains the labels (train.csv)

#### Test dataset
Grayscale intensities- with 96 rows/data, 196 columns/features, column 197 contains the labels (test.csv)

Tip: Only the .csv files are needed for the classification, the images are for illustration purposes.

## Application
In the Jupyter notebook 'Handwritten Greek letters classification.ipynb' various classification methods are performed such as Neural Networks, k-Nearest Neighbors, Gaussian Naive Bayes, Random Forest and Logistic Regression. Confusion matrices are computed to illustrate the effectiveness of each method. 
