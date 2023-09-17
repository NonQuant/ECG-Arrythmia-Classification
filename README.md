# ECG Classification using 1D CNN

## Dataset

The dataset was taken from [here](https://www.kaggle.com/datasets/shayanfazeli/heartbeat) (arrhytmia dataset)

## Dataset details

* Number of Samples: 109446
* Number of Categories: 5
* Sampling Frequency: 125Hz
* Data Source: Physionet's MIT-BIH Arrhythmia Dataset
* Classes: ['N': 0, 'S': 1, 'V': 2, 'F': 3, 'Q': 4]

## Model

The input shape: 187 per sample

Trained weights for model(in .h5 format) you can find [here](https://drive.google.com/file/d/1tigPhDsL_2jkstqb1C0Xl6lPtq0PckZ_/view?usp=drive_link)

This model achieved 96.9% average precision and 94% test accuracy