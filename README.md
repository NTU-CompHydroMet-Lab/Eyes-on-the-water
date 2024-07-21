# Eyes on the Water – Thousands of citizen photos train AI to monitor river pollution

## Overview
This repository contains the final models, data, and supporting documentation for the "Eyes on the Water" project, which uses AI to monitor river health through citizen-collected photos.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/eyes-on-the-water.git
   cd eyes-on-the-water

2. Install the required packages:
   ```bash
   # You can either use the venv or conda environment
   python -m venv env
   source env/bin/activate   # On Windows use `env\Scripts\activate`
   pip install -r requirements.txt
   
   # Or create a conda environment
   conda env create -n eyes-on-the-water
   conda activate eyes-on-the-water
   pip install -r requirements.txt

3. Install torch & torchvision
   Please install the appropriate version of torch and torchvision based on your system configuration. You can find the installation instructions [here](https://pytorch.org/get-started/locally/).

## Data

Please download the data from the following link and place it in the `EOTW_data` directory:

[Eyes on the Water Data link](https://drive.google.com/drive/folders/1EpFzymSZf87BqfKMvbiT1NOkVhsfK5jI?usp=sharing)


## Models
In this project, we use two models: YOLOv8 for object detection and CTran for image classification. Please download the models from the following link and place them in the `EOTW_models` directory:

[Eyes on the Water models link](https://drive.google.com/drive/folders/1yrm4_oMC-lxO65D2hf1S6ieb2dsSPV_0?usp=sharing)


## Demo

- **Demos/Image classification.ipynb**: Demo notebook for image classification using the CTran model.
- **Demos/Object detection.ipynb**: Demo notebook for object detection using the YOLOv8 model.