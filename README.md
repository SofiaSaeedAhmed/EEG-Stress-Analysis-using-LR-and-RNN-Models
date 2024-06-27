# EEG-Stress-Analysis-using-LR-and-RNN-Models
This repository showcases the models built for a year-long project conducted at the University of Nottingham Malaysia Campus.
## Project Overview
This project focuses on analyzing EEG data to assess stress levels using Logistic Regression (LR) and Recurrent Neural Network (RNN) models. The models are designed to work with EEG samples from two types of headsets - Muse and Emotiv.
## Models
The classes which the models classified can be identified by the number in the filename - 1 signifies the model classified EEG samples which indicate non-stress and stress, while 2 signifies the model classified low stress and high stress. The models can be conjoined to form a pipeline architecture to classify EEG samples into three classes: No stress, low stress and high stress.
<div align="center">
  <img src="https://github.com/anshali15634/EEG-Stress-Analysis-using-LR-and-RNN-Models/assets/136955668/1a1d6b6a-5d61-4a61-8ab1-dffa31155101" alt="Model Architecture" width="500"/>
  <p><em>Model Pipeline Architecture</em></p>
</div>

## Dataset
The models were trained using the SAM-40 dataset. Link to dataset: https://doi.org/10.6084/m9.figshare.14562090.v1

## Contributors
@anshali15634 - developed the initial structure and architecture of the RNN models and retrained all models to ensure compatibility with EEG samples from Muse S (Gen 2) headset and 32-channel Emotiv headset. Also conducted comprehensive parameter tuning and testing to increase the performance of all models and further optimised the models by reducing channel count for training of models.

@SofiaSaeedAhmed - developed the initial structure and architecture of the Logistic Regression (LR) models for EEG samples from 32-channel Emotiv headset.
