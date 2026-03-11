### Fruit Freshness Detection using CNN

#### Project Overview

This project builds a computer vision model to classify fruit images as fresh or rotten using deep learning techniques. The goal is to explore how machine learning can assist with automated food quality inspection, which can help reduce food waste and improve quality control in supply chains.

The model is trained on a labeled dataset of fruit images and uses Convolutional Neural Networks (CNN) and transfer learning techniques to learn visual patterns associated with freshness and spoilage.

#### Dataset

Dataset used in this project:

Fresh vs Rotten Fruit Images
https://www.kaggle.com/datasets/abdulrafeyyashir/fresh-vs-rotten-fruit-images

The dataset contains images of multiple fruit categories labeled as:
* Fresh
* otten

Example fruit types include:
* Apples
* Bananas
* Oranges

#### Project Objectives

The main research question is:

Can a machine learning model accurately classify fruit images as fresh or rotten?

This project aims to:
* Explore image data using Exploratory Data Analysis (EDA)
* Perform data cleaning and preprocessing
* Build a baseline CNN model
* Evaluate model performance using classification metrics
* Prepare the pipeline for further improvements using transfer learning


#### Exploratory Data Analysis (EDA)

Key steps include:
* Visualizing sample images
* Checking class balance
* Inspecting pixel distributions
* Identifying potential labeling or image quality issues

#### Data Preprocessing

The following preprocessing techniques were applied:
* Image resizing (standardized input size)
* Pixel normalization
* Data cleaning
* Train / validation split
* Data augmentation

#### Baseline Model

Logistic regression was implemented as the baseline model.
