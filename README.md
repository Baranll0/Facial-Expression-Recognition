![Duygu Tanıma](https://i.imgur.com/qlLnaG0.jpg)
# Facial Expression Recognition with Convolutional Neural Network

## Overview

This project implements a Convolutional Neural Network (CNN) for facial expression recognition using the FER2013 dataset. The CNN is built using the Keras library and trained to recognize facial expressions such as anger, fear, surprise, and more.

## Dataset

The FER2013 dataset is used for training and testing the model. The dataset contains facial expression images labeled with different emotions.

## Dependencies

- **Python 3**
- **numpy**
- **pandas**
- **matplotlib**
- **keras**
- **PIL**

Install the required dependencies using:

```bash
pip install numpy pandas matplotlib keras pillow
```
### 1. Clone the repository
```bash
git clone https://github.com/Baranll0/Facial-Expression-Recognition.git
```
### 2. Run the Jupyter Notebook:
```bash
jupyter notebook
```
Open the notebook and execute each cell step by step.

## 1. Training the Model:

The model is trained using the FER2013 training dataset.
Checkpointing is used to save the best weights during training.

## 2. Model Evaluation:

Evaluate the model on the PublicTest and PrivateTest datasets.

## 3. Inference:

Use the trained model for facial expression recognition on new images.

# Files
**'fer2013.csv'**: CSV file containing facial expression data.

**'face_model.json and face_model.h5'**: Model architecture and weights.

**'emojis/'**: Folder containing emoji images corresponding to different facial expressions.

# Results

* Display of training and validation loss and accuracy during training.
* Evaluation of the model on the PrivateTest dataset.
* Inference on new images with visualization of classification results.#
