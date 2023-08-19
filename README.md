# Next Word Prediction Using LSTM Model

Predict the next word in a sentence using a Long Short-Term Memory (LSTM) model. This project utilizes natural language processing and deep learning techniques to provide accurate word predictions.

## Table of Contents

- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

This project aims to develop an LSTM-based model that predicts the next word in a sentence. The model is trained on a dataset containing a vast collection of text data, enabling it to learn patterns and relationships within the language.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Mohshaikh23/Next-Word-Prediction-Model.git
cd next-word-prediction
```

2. Install the required libraries using pip:

```bash
pip install -r requirements.txt
```

## Usage

1. Run the Jupyter Notebook `next_word_prediction.ipynb` to preprocess the data, build the LSTM model, and generate predictions.

2. Input a partial sentence, and the model will predict the next probable word based on the context.

## Dataset

The dataset used for training the model consists of a diverse range of text data, including articles, books, and web content. It's preprocessed to remove noise and create a vocabulary for the model.

## Model Architecture

The LSTM model is a type of recurrent neural network (RNN) that is particularly effective for sequence data. It's designed to capture long-range dependencies and patterns within text data. The model architecture consists of an embedding layer, LSTM layers, and a dense layer for prediction.

## Results

The model's accuracy is evaluated using metrics such as perplexity and accuracy of predicted words. Sample sentences are provided to demonstrate the model's capability in generating coherent and contextually relevant predictions.

## Contributing

Contributions are welcome! If you have suggestions for improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.