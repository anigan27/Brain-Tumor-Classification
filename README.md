# Brain Tumor Classification

## Description

This repository has notebooks that are used for CNN based models trained on the following dataset
(https://www.kaggle.com/datasets/sartajbhuvaji/brain-tumor-classification-mri).

## Files

### Baseline CNN model
github_GT_baseline_no_augmentation.ipynb: 
This contains code to train the baseline CNN model on the training data after normalizing and resizing the images
The model is evaluated on the test dataset

### Image augmentation and transfer learning using EfficientNet
github_GT_transfer_learning_and_image_augmentation.ipynb: 
This contains code to add image augmentation including rotation and then train a EfficientNet based transfer learning model on the training data
The model is evaluated on the test dataset

### Selective augmentation
github_GT_selective_augmentation.ipynb: 
This contains code to selectively augment images from test data into training data for classes that underperformed in terms of recall (e.g. glioma tumor)  and then retrain a EfficientNet based transfer learning model on the new training data
The model is evaluated on the test dataset

### Finding mislabelled training data
github-cleanlab-find-mislabeled-images.ipynb: 
This contains code to filter and remove likely anomalies (mislabelled images) from the training data using CleanLab's anomaly detection tool
The model is evaluated on the test dataset


## Authors

Anika Ganu

## Version History

* 0.1
    * Initial Release


