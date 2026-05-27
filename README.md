# Music-genre-classification using CRNN
## overview

This project focuses on classifying music tracks into different genres using a Convolutional Recurrent Neural Network (CRNN). The model combines the power of Convolutional Neural Networks (CNN) for feature extraction and Recurrent Neural Networks (RNN/LSTM) for sequential learning from audio data.

The system analyzes audio signals and predicts the corresponding music genre based on extracted audio features such as Mel Spectrograms and MFCCs.

## Features
* Automatic music genre classification
* Audio preprocessing and feature extraction
* Mel Spectrogram and MFCC generation
* Deep learning using CRNN architecture
* Multi-class genre prediction
* Performance evaluation using classification metrics
* Visualization of training and prediction results
## Technologies Used
* Python
* TensorFlow / Keras
* Librosa
* NumPy
* Pandas
* Matplotlib
* Scikit-learn
## Dataset

The dataset contains audio tracks categorized into multiple music genres such as:

* Classical
* Jazz
* Pop
* Rock
* Hip-Hop
* Blues
* Metal
* Country
* Disco
* Reggae

## Dataset Sources:

GTZAN Music Genre Dataset
[Link](/kaggle/input/datasets/carlthome/gtzan-genre-collection)
## Project Workflow
### 1. Data Collection

Collected labeled music genre audio datasets from publicly available sources.

### 2. Audio Preprocessing

Performed preprocessing on audio signals:

* Audio loading
* Noise handling
* Resampling
* Signal normalization
### 3. Feature Extraction

Extracted important audio features using Librosa:

* MFCC (Mel Frequency Cepstral Coefficients)
* Mel Spectrograms

### 4. Model Building

Built a CRNN-based deep learning architecture:

* CNN layers for spatial/audio feature extraction
* Max Pooling layers
* Recurrent (LSTM/GRU) layers for sequential learning
* Dense output layer for genre classification
### 5. Model Training

Trained the model using:

* Adam Optimizer
* Categorical Crossentropy Loss
* Batch Training and Validation
### 6. Prediction & Evaluation

Predicted music genres and evaluated model performance using classification metrics.

## Evaluation Metrics

The model performance was evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix

## Results
Successfully classified music genres using CRNN architecture
Learned both spatial and temporal audio patterns effectively
Achieved good multi-class classification performance on music datasets

## Author
Saideepak
## GitHub Repositorylink

(https://github.com/Saideepak2004/Music-genre-classification.git)
