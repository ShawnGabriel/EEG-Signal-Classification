# EEG Signal Classification with Keras

This repository reimplements the EEG signal classification pipeline from the official [Keras example](https://keras.io/examples/timeseries/eeg_signal_classification/). The pipeline demonstrates how to preprocess EEG data, extract meaningful features, and use a deep learning model to classify motor imagery tasks based on EEG signals.

---

## Features

- **EEG Data Preprocessing**:
  - Standardizes and reshapes EEG data for training.
  - Applies appropriate windowing to split continuous EEG signals into smaller segments.
  
- **Deep Learning Model**:
  - Implements a convolutional neural network (CNN) to classify EEG data.
  - Optimized for multichannel EEG input.
  
- **Reproducibility**:
  - Step-by-step code and modular functions for clear understanding and easy extension.

