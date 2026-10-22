# EEG Driver Drowsiness Detection Using MATLAB

An EEG-based driver drowsiness detection system developed in MATLAB using digital signal processing and Support Vector Machine (SVM) classification to identify alert and drowsy states from EEG recordings.

## Overview

Driver drowsiness is an important road-safety concern that can reduce attention and reaction time. This project explores the use of Electroencephalography (EEG) signals and machine learning to classify brain activity into two states: **Alert** and **Drowsy**.

The system processes EEG recordings, extracts frequency-band power features, trains an SVM classifier, and evaluates its performance using standard classification metrics. A MATLAB interface displays the predicted state and the corresponding EEG waveform for a selected recording.

## Objectives

- Load and analyse a labelled EEG dataset.
- Apply digital signal processing techniques to EEG signals.
- Extract frequency-band power features from multiple EEG channels.
- Train a Support Vector Machine classifier for binary classification.
- Evaluate the model using accuracy, sensitivity, specificity, precision, and a confusion
