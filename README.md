# Skin Cancer Image Classification

## Overview

Within this repository, a Jupyter notebook is housed, dedicated to the task of skin cancer image classification through the application of machine learning techniques.
The overarching objective of this project lies in the precise categorization of skin cancer images, a pivotal pursuit aimed at facilitating early detection and diagnosis.

## Table of Contents

1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Dataset](#dataset)
5. [Model](#model)
6. [Results](#results)

## Introduction

This notebook leverages the EfficientNetB0 pretrained model to perform binary classification distinguishing between malignant and benign skin lesions. 

Serving as an illustrative project, it serves the dual purpose of highlighting fundamental principles within the domain of deep learning while underscoring the essentiality of such methodologies in the context of medical image classification.
## Installation

To install necessary libraries, run the command provided here.

```bash
pip install -r requirements.txt
```
## Dataset

The Skin Cancer Image Dataset is a comprehensive collection comprising approximately 5000 high-resolution images representative of malignant melanoma and an equivalent number of images depicting benign skin lesions.
Curated meticulously for academic research purposes, this dataset addresses the exigent need for sophisticated machine learning models dedicated to skin cancer classification and diagnosis.
## Usage

Utilize Jupyter Notebook, Jupyter Lab, or any IDE that supports .ipynb files. 

Run all cells, and feel free to modify hyperparameters as needed.
## Model
This notebook strategically leverages the capabilities of the pre-trained EfficientNetB0 model, a SOTA neural architecture renowned for its efficiency and effectiveness in image classification tasks.
 By harnessing the transfer learning paradigm encapsulated within EfficientNetB0, this project endeavors to enhance the performance of skin cancer image classification. 
 The model has been fine-tuned to discern intricate patterns and features indicative of malignant and benign skin lesions, thereby contributing to the overarching goal of advancing early detection and diagnostic precision in the realm of dermatological pathology.

## Results

* **train/validation/test**: 90/05/05
* **CrossEntropyLoss**
* **Adadelta**:
  * rho=0.9
  * eps=1e-6
* **epochs**: 10
* **Early Stopping**:
  * **patience**: 2
  * **delta**: 0.001

The model accuracy stays consistent in the range of > 92% on the test data.
