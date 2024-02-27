# Bird Recogntion

This model is made in collaboration with my fellow collegue Kartik Yadav (email: kartik134yadav@gmail.com,  github: https://github.com/kartik912)

## Overview
This project aims to classify audio clips into two categories: Capuchin bird calls and non-Capuchin bird calls. It leverages TensorFlow and TensorFlow I/O to process and analyze audio files, applying machine learning techniques to distinguish between these two types of sounds.

# Getting Started

## Prerequisites
Python 3.6+
TensorFlow 2.x
TensorFlow I/O
Matplotlib


## Installation

Clone the repository:

git clone https://github.com/yourusername/capuchin-bird-audio-classification.git

## Navigate to the project directory:

cd capuchin-bird-audio-classification

## Install the required packages:

pip install tensorflow tensorflow-io matplotlib

## Running the Model

Ensure your audio data is organized into two directories: Parsed_Capuchinbird_Clips and Parsed_Not_Capuchinbird_Clips within the Data directory.

## Run the main script:

python main.py


## Usage


The model is trained on a dataset of audio clips, with each clip labeled as either a Capuchin bird call or non-Capuchin bird call. The script processes these audio files, converts them into spectrograms, and feeds them into a convolutional neural network (CNN) for classification.

## Preprocessing

Audio files are loaded and preprocessed to ensure they are in the correct format for the model. This includes resampling to a 16kHz mono audio, converting to spectrograms, and zero-padding to ensure all inputs are the same length.

## Training

The model is trained using a dataset of preprocessed audio spectrograms, with labels indicating whether each spectrogram represents a Capuchin bird call or not. The model's architecture includes convolutional layers, max pooling, and dense layers to achieve classification accuracy.

## Evaluation

The model's performance is evaluated using metrics such as loss, precision, recall, and accuracy. The evaluation dataset is separate from the training dataset to ensure the model's ability to generalize to unseen data.

## Contributing
Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss potential improvements or bug fixes.


## Contact
For any questions or issues, please open an issue on this repository.
