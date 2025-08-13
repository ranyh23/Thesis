# Thesis
This repository contains all the code used in the process of preparing my dataset and running my YOLOv11n model

All files have been carefully commented to show the purpose of each line/function. Below is a list of the files, in the order I ran them:

List of files:

This script is used to split the unsplit label studio dataset into training, test and validation sets
1. script_for_splitting_dataset.ipynb

This script is used to apply cropping to the data, and generate matching label files for the new crops
3. crop_dataset_script.ipynb

This script is used to add noise to our training images
4. add_salt_pepper_noise.ipynb

This script is used to train the model + run inference on five unlabeled images and calculate the average class confidence
5. yolov11n_script_augmentation_setup.ipynb

This script generates images meant to test for shortcut learning as well as run inference using the previously trained model
6. shortcut_learning.ipynb

This script prepares a subset of our training data
7. 11_percent_datasplit.ipynb

This script trains a new yolov11n model on the subset
8. yolo11_restricted_datasets.ipynb

-------------------------------------------------------------------------------------------------------------------------------------------------------------

The models and scripts used in the analysis of robustness were accessed from the following links:

Yolov11 + EfficientNet: https://github.com/JYe9/YOLO11_EfficientNet

D-Fine: https://github.com/Peterande/D-FINE

-------------------------------------------------------------------------------------------------------------------------------------------------------------
