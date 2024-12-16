Udacity Car-Sim Dataset
Overview:

This repository contains data collected from Udacity's Self-Driving Car Simulator. The dataset consists of images captured by three front-facing cameras (left, center, right) and corresponding steering angles.

Data Format:

Images:
Stored in subdirectories left, center, and right.
Format: JPG
Steering Angles:
Stored in a CSV file named driving_log.csv.
Each row contains a timestamp and the corresponding steering angle.
Usage:

This dataset can be used for various tasks, including:

Training and validating self-driving car models: Use the images and steering angles to train models that can predict steering angles based on camera input.
Data augmentation: Generate additional training data by applying transformations like flipping, rotation, and brightness adjustments.
Behavioral cloning: Train a model to imitate human driving behavior by learning from the steering angles.
