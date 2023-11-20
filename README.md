# Text Emotion Recognition using RNN Neural Network model 

## Overview
This project is designed to classify textual data into six emotions: joy, sadness, anger, hate, love, and surprise. Utilizing a pre-trained Word2Vec model and BiLSTM layers, the neural network offers sophisticated emotion recognition capabilities.

## Dataset
The dataset, `emotions.csv`, includes a diverse collection of sentences and tweets, each associated with one of the specified emotions. It serves as the basis for training and evaluating the neural network.

## Features
- **BiLSTM Layers**: Leverages Bi-directional Long Short-Term Memory layers for effective contextual understanding in text.
- **Word2Vec Integration**: Incorporates a pre-trained Word2Vec model for robust word embeddings.
- **Data Preprocessing**: Details the process of loading, cleaning, and processing data from the database.
- **Model Evaluation**: Highlights an accuracy of 88.3% on test data.

## Requirements

This project requires the following libraries:

- pandas
- TensorFlow
- numpy
- scikit-learn
- gensim
- nltk
- matplotlib

## Installation
```bash
git clone https://github.com/thejus03/Text-Emotion-Neural.git
cd TER
pip install pandas tensorflow numpy scikit-learn gensim nltk matplotlib
```

## Downloading the Pre-trained Word2Vec Model

To utilize the pre-trained Word2Vec model in this project, follow these steps:

1. Visit the Kaggle dataset page for the Google Word2Vec model: [Google Word2Vec Kaggle Dataset](https://www.kaggle.com/datasets/sugataghosh/google-word2vec).
2. Download the dataset from the provided link.
3. Extract the downloaded file.
4. Place the extracted Word2Vec model **.bin** file into the `TER` folder, which contains the `emotions.ipynb` and `emotions.csv` files.

This will ensure that the Jupyter notebook can correctly locate and use the Word2Vec model for processing the data.



