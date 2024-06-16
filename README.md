# Chest X-ray Image Classification for Pneumonia Detection using CNN

This repository contains the implementation of a Convolutional Neural Network (CNN) for the classification of pneumonia from chest X-ray images. This project is part of a dissertation submitted to the University of Essex, Department of Mathematical Sciences.

## Overview

Pneumonia is a serious lung infection affecting the alveoli and is one of the leading causes of mortality among children worldwide. Early detection and diagnosis are crucial for effective treatment. Chest X-rays are commonly used for diagnosing pneumonia, but the manual interpretation of these images is time-consuming and prone to errors, especially in resource-limited settings.

This project leverages deep learning techniques to develop an automated tool for pneumonia detection using chest X-ray images. The proposed method employs Convolutional Neural Networks (CNN) to classify chest X-rays as either normal or indicative of pneumonia.

## Datasets

The following datasets were utilized for training and evaluation:

- Chest X-ray 14 dataset
- Pediatric Chest X-rays for Pneumonia Detection
- MIMIC Chest X-ray
- Open-I Indiana Dataset
- MC Dataset
- Shenzhen Dataset
- KIT Dataset
- JSRT Dataset
- Pneumonia Dataset from Kaggle
- RSNA Pneumonia Dataset
- NIH Chest X-ray Dataset

These datasets provide a diverse collection of chest X-ray images, which are crucial for training robust models.

## Methodology

### Pre-processing

Image pre-processing steps include normalization, resizing, and augmentation to enhance the model's ability to generalize across different datasets.

### Model Architecture

Several CNN architectures were explored, including VGG-16, Inception Net, Dense Net, ResNet-50, and Efficient Net B0. The final model was selected based on its performance on the validation set.

### Training

The model was trained using the chest X-ray images from the Kaggle dataset, achieving an accuracy of 79.97% on the holdout dataset.

## Results

The proposed method demonstrates a practical approach for automated pneumonia detection with promising accuracy. Detailed results and performance analysis can be found in the dissertation.

## Conclusion

This project showcases the potential of deep learning in medical image analysis, particularly for the diagnosis of pneumonia from chest X-ray images. The implementation of CNNs can significantly aid radiologists by providing quick and accurate preliminary assessments, thus improving patient outcomes.
