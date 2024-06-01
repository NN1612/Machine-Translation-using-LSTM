# Machine-Translation-using-LSTM
This repository contains Python code for training and using a basic sequence-to-sequence (Seq2Seq) model for machine translation using LSTM.

## Overview
The provided code implements a basic Seq2Seq model using LSTM layers for machine translation. It translates English sentences to French sentences using a dataset stored in a text file (fra.txt). The model is trained using the RMSprop optimizer and categorical cross-entropy loss function.

## Requirements
* Python 3.x
* Keras
* NumPy

## Usage

* Clone this repository:
git clone <repository_url>

* Navigate to the repository directory:
cd <repository_name>

Ensure that the required dependencies are installed. You can install them using pip:
pip install -r requirements.txt

* Download the dataset fra.txt or deu.txt and place it in the root directory.

* Run the training script:
This will train the model using the dataset and save the trained model.
