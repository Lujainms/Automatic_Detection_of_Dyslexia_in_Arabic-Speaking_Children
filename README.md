# Automatic Detection of Dyslexia in Arabic-Speaking Children

# Overview
This repository contains the YUSR Arabic Dyslexia Dataset, a synthetic Arabic handwritten dataset designed for dyslexia detection in Arabic-speaking children using deep learning models.

The dataset was constructed using handwritten Arabic letters and augmentation techniques to simulate dyslexic handwriting patterns.


# Dataset Description

The dataset includes:

- Arabic handwritten isolated letters
- Train / Validation / Test splits
- Dyslexic samples
- Non-Dyslexic samples


# Dataset Construction

The dataset was constructed using the DHAD dataset and several preprocessing and augmentation techniques such as:

- Rotation
- Shifting
- Flipping
- Dot manipulation
- Elastic distortion

These transformations were applied to simulate dyslexic handwriting characteristics.


# Models Used

- EfficientNetB0 Baseline
- ResNet50 Baseline
- MobileNetV2 Baseline
- Fine-Tuned MobileNetV2 (10 Layers)
- Attention Layer with Fine-Tuned MobileNetV2 (10 Layers)
- Fine-Tuned MobileNetV2 (20 Layers)
- Per-Letter Classification Using Fine-Tuned MobileNetV2 (20 Layers)


# Research Purpose

This work aims to support the early detection of dyslexia in Arabic-speaking children and address the lack of publicly available Arabic dyslexic handwriting datasets.


# Authors
College of Computer and Information Sciences  
Al Imam Mohammad Ibn Saud Islamic University
- Danah Sebhan Al-Ghezii
- Ghaida Saeed Al-Dowsary
- Lujain Mohammed Al-Suhaibani
- Reema Khaled Al-Obaid


