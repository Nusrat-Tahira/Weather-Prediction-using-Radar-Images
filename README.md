# Weather-Prediction-using-Radar-Images

## Overview
This document outlines the folder structure, contents, and purposes of each component in the "Weather-Prediction-using-Radar-Images" project. The project leverages radar images to predict weather conditions, utilizing various datasets and notebooks for training and testing machine learning models.

## Folder Structure
Weather-Prediction-using-Radar-Images/
├── radar_images/
│   ├── RDR_PSN_202306230000.png
│   ├── RDR_PSN_202306230001.png
│   └── ... (more radar images)
├── dataset/
│   ├── 12framesRGB.h5
│   ├── 24framesRGB.h5
│   └── 36framesRGB.h5
├── training_file.ipynb
├── testing_models.ipynb
├── requirements.txt
└── output/

## Folder Descriptions
1. radar_images/
This directory contains radar images used as input data for weather prediction models. Each image filename corresponds to a specific timestamp, formatted as RDR_PSN_YYYYMMDDHHMM.png. 

### Example Files:
RDR_PSN_202306230000.png: Radar image for June 23, 2023, at 00:00.
RDR_PSN_202306230001.png: Radar image for June 23, 2023, at 00:01.
… and so on for additional timeframes.

2. dataset/
This folder houses datasets in HDF5 format, which are structured to facilitate model training and testing. Each file contains a series of RGB frames representing different weather scenarios.

### Example Files:
12framesRGB.h5: Contains 12 frames of RGB images for training/testing.
24framesRGB.h5: Contains 24 frames of RGB images.
36framesRGB.h5: Contains 36 frames of RGB images.

3. training_file.ipynb
This Jupyter Notebook file is designed for training the weather prediction model. It provides the necessary code to load datasets, preprocess radar images, and train the selected machine learning or deep learning model.

4. testing_models.ipynb
This Jupyter Notebook file is utilized for testing and evaluating the performance of the trained weather prediction model. It contains code to make predictions using new radar image inputs and assess the accuracy of the results.

5. requirements.txt
This file lists all the Python packages required to run the project. It includes specific versions of libraries needed for data analysis, model training, and visualization. To install the required packages, execute the following command:
pip install -r requirements.txt

7. output/
The output folder is designated for storing results generated from model predictions and evaluations. This directory may include prediction logs, visualizations, or any other relevant output generated after running the training or testing notebooks.

## Conclusion
This folder structure is organized to facilitate the development and evaluation of weather prediction models using radar images. Ensure to keep datasets and images current to maintain the accuracy and effectiveness of the predictions.
----------------------------------------------------------------------------------------------------------------------------
Feel free to modify any parts of the file to better suit your project or to add any additional details that may be relevant!
