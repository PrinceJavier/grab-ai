Grab AI for SEA Challenge - Safety
by Prince Joseph Erneszer Javier

README
======

Notes on Virtual Machine and Environment 
========================================
Virtual Machine: AWS c5.9xlarge 
Operating System: Deep Learning AMI (Ubuntu) Version 23.0 
Environment: tensorflow_p36 - the yaml file is saved
Storage Size: 85 GB


Notebooks
=========
grab-ai-predicting - this notebook is used to predict on new dataset. For predicting on new data, only run this notebook

grab-ai-preprocessing-eda - this notebook contains data loading and transformation, feature engineering, and sampling for model training

grab-ai-training - this notebook is used to train and save models

grab-ai-testing - this notebook is used to test trained models on unseen test dataset


Folders
=======
data - contains the datasets for training and predicting
models - contains trained models
prediction - contains saved predictions as CSV
results - contains validation accuracy results during model training
scalers - contains scalers fit on training data