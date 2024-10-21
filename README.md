# Weather Prediction Using Radar Images - Setup Guide

## Project Overview
This project utilizes radar images to predict weather conditions. It includes training and testing notebooks, datasets, and radar images.

## Folder Structure
```
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
```
## Setup Process

### Step 1: Install Anaconda
Download and install Anaconda:
- [Anaconda](https://www.anaconda.com/products/distribution#download-section)

### Step 2: Create a Conda Environment
1. Open your terminal or Anaconda Prompt.
2. Navigate to the project directory:
   ```bash
   cd path/to/Weather-Prediction-using-Radar-Images
   ```
3. Create a new Conda environment:
   ```bash
   $ conda create --name weather-prediction-env python=3.7.16
   ```
4. Activate the environment:
   ```bash
   $ conda activate weather-prediction-env
   ```
### Step 3: Install Required Packages
1. Install the required packages:
   ```bash
   $ pip install -r requirements.txt
   ```
2. Verify installation:
   ```bash
   $ pip list
   ```
### Step 4: Open Jupyter Notebook
1. Launch Jupyter Notebook:
   ```bash
   $ jupyter notebook
   ```
2. In your browser, navigate to the project folders.

### Step 5: Run the Training Notebook
1. Open training_file.ipynb.
2. Review and run the cells to train your model.

### Step 6: Run the Testing Notebook
1. Open testing_models.ipynb.
2. Adjust code as needed and run the cells to test your model.

### Step 7: Check the Output Folder
Review the output/ folder for results and logs.

### Step 8: Deactivate the Conda Environment (Optional)
To deactivate the environment, run:
   ```bash
   $ conda deactivate
   ```
### Conclusion
You have successfully set up your environment and executed your weather prediction project using radar images. Adjust the datasets and model parameters as necessary to optimize performance.
