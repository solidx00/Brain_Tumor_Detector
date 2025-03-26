# Brain_Tumor_Detection

This repository contains a deep learning approach for detecting brain tumors from MRI images. A custom Convolutional Neural Network (CNN) model was designed and trained from scratch, alongside experiments with the pretrained InceptionV3 model using transfer learning techniques.

## Project Overview

The primary goal is to classify MRI scans accurately into categories representing the presence or absence of a brain tumor. The project compares the effectiveness of:

A CNN model built and trained from scratch.

Fine-tuned pretrained model: InceptionV3.

The models were trained and evaluated on a publicly available MRI dataset on Kaggle consisting of labeled images for brain tumor classification.

### Dataset
```bash
[https://drive.google.com/drive/folders/16Minx_KeL9pgm8v5cT_Q4lY08qn4oxBo?usp=sharing](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)
```

## Weights

### Our CNN
```bash
https://drive.google.com/drive/folders/16Minx_KeL9pgm8v5cT_Q4lY08qn4oxBo?usp=sharing
```
### InceptionV3
```bash
https://drive.google.com/drive/folders/19aQkp5AfOOdE0JPFt0_c1acely6X-sKS?usp=sharing
```

### Accuracy Results
| Our Model   | InceptionV3
| :---: | :---: |
| 0.96   | 0.88

### Loss Results
| Our Model  | InceptionV3
| :---: | :---: |
| 0.11   | 0.45 

