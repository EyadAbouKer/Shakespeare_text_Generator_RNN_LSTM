# Shakespeare_text_Generator_RNN_LSTM
A Recurrent Neural Network that uses LSTM Architecture

## Overview
This project implements a text generator using a Recurrent Neural Network (RNN) with Long Short-Term Memory (LSTM) architecture. The model is trained on a dataset of Shakespearean text strings, consisting of 6270 strings for training and 2790 strings for testing. Each string is comprised of 100 characters.

## Project Structure
Recurrent Neural Network with LSTM Design: The RNN architecture used in this project is based on LSTM cells to address the vanishing gradient problem.

Download Shakespeare Dataset: Instructions and code snippets to download the Shakespeare dataset from a Google Drive repository.

Needed Libraries: Installation commands for required libraries, including Torch.

Data Preparation: Loading and preprocessing the training and testing datasets, including mapping characters to indexes for feeding into the RNN.

## Main Model: 
Implementation of the RNN model, including embedding, LSTM layers, and linear transformation.

## Training:
Training loop with hyperparameters such as loss function, epochs, learning rate, hidden size, number of layers, embedding dimension, and dropout. Instructions for running the training loop and monitoring training progress.

## Testing:
Evaluation of the trained model on the test set to compute the test loss.

# Text Generation: 
Function to generate text using the trained RNN model, with an option to specify the length of the generated text.

## Usage
Download Dataset: Run the provided code to download the Shakespeare dataset, it will automatically set everything up for you if you are running on Google Colab.
Training the model may take a significant amount of time on the CPU. Switching to GPU can significantly speed up the training process. Make sure to adjust the hardware accelerator settings accordingly in the runtime environment.
