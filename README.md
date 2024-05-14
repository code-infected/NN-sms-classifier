# Neural Network SMS Text Classifier

This project implements a machine learning model using neural networks to classify SMS messages as either "ham" or "spam". 

## Overview

The goal of this project is to develop a model that can accurately classify SMS messages as either normal ("ham") or spam. The model is trained using the SMS Spam Collection dataset, which consists of labeled SMS messages.

## Dataset

The SMS Spam Collection dataset has been split into train and test sets. The train set is used for training the model, while the test set is used for evaluating its performance.

## Model Architecture

The model architecture consists of an embedding layer followed by a flatten layer and a dense layer with a sigmoid activation function. The model is compiled with the Adam optimizer and binary cross-entropy loss.

## Usage

To use the model, you can call the `predict_message` function with a message string as input. The function returns a list containing the likelihood of the message being "ham" or "spam" and the predicted class.

## Evaluation

The model's performance is evaluated using test messages, and it achieves a high accuracy in classifying both "ham" and "spam" messages.

## Further Improvements

- **Hyperparameter Tuning**: Experiment with different hyperparameters to optimize the model's performance.
- **Handling Imbalance**: Explore techniques to handle class imbalance if present in the dataset.
- **Feature Engineering**: Consider adding additional features or preprocessing steps to improve the model's accuracy.

## Credits

This project is part of a challenge and utilizes resources provided by FreeCodeCamp.

## License

This project is licensed under the MIT License - see the [LICENSE] file for details.
