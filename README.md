# Arabic-Name-Generation-with-LSTM
This project demonstrates how to use a Long Short-Term Memory (LSTM) neural network to generate names based on a dataset of names. The model is trained to predict the next character in a sequence of characters, given the previous characters.
## Dataset
The datasets used in this project are a text files containing a list of arabic names for boys and girls obtained via scrapping wikipedia and equally a text file containing the most famous tunisian last names deduces from the web . The files are preprocessed to divide the names into sequences of length 3 and create a mapping of unique characters to integers. The final output is a set of input-output pairs encoded as integers.

## Model
The model used in this project is a single-layer LSTM neural network with 128 units. The model is trained for 100 epochs using the Adam optimizer and categorical cross-entropy loss function. The model is then used to generate new names by predicting the next character in the sequence based on the previous characters.

## How to use 
To use this project, you can clone the repository and run the name_generation.ipynb  cells to train the model and generate new names. You can modify the text file containing the names to train the model on a different set of names.

## Requirements

- Python 3.6 or higher
- Keras 2.2.4 or higher
- NumPy 1.14.3 or higher
