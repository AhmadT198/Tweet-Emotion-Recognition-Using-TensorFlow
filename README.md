# Tweet Emotion Recognition

This repository contains a Python notebook for performing emotion recognition on tweets using TensorFlow. The notebook includes steps for importing the data, tokenizing the tweets, preparing the data for training, building and training a Bidirectional LSTM model, evaluating the model's performance, and visualizing the results.

## Installation

To run the notebook, you need to install the required libraries. You can install them via pip:

```
pip install nlp
pip install datasets
```

## Task Explanations

### Task 3: Importing Data

1. Importing the Tweet Emotion dataset.
2. Creating train, validation, and test sets.
3. Extracting tweets and labels from the examples.

### Task 4: Tokenizer

1. Tokenizing the tweets.

### Task 5: Padding and Truncating Sequences

1. Checking the length of the tweets.
2. Creating padded sequences.

### Task 6: Preparing the Labels

1. Creating classes to index and index to classes dictionaries.
2. Converting text labels to numeric labels.

### Task 7: Creating the Model

1. Creating the model architecture.
2. Compiling the model.

### Task 8: Training the Model

1. Preparing a validation set.
2. Training the model.

### Task 9: Evaluating the Model

1. Visualizing training history.
2. Preparing a test set.
3. A look at individual predictions on the test set.
4. A look at all predictions on the test set.

## Usage

To run the notebook, simply open it in a Jupyter Notebook environment or any compatible platform.

## License

This project is licensed under the MIT License.
