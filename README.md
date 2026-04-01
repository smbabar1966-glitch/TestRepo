# Seq2Seq Language Translation (German → English)

A deep learning project implementing neural machine translation using an LSTM-based Seq2Seq model in PyTorch.

## Overview

This project implements a neural machine translation system using a Sequence-to-Sequence (Seq2Seq) model with an LSTM encoder-decoder architecture in PyTorch.

The model translates German sentences into English using the Multi30k dataset.

## Model Architecture

* Encoder: LSTM-based encoder
* Decoder: LSTM-based decoder
* Seq2Seq wrapper
* Teacher forcing during training

## Features

* German-to-English translation
* Tokenization and vocabulary mapping
* Padding and batching
* Training and evaluation loops
* BLEU score evaluation
* Perplexity tracking

## Technologies Used

* Python
* PyTorch
* TorchText
* NumPy
* Matplotlib
* spaCy
* NLTK

## Dataset

Multi30k German-English translation dataset

## Results

* Training Loss: ~5.5 (short run)
* Validation Loss: ~5.0
* BLEU Score: Low due to limited training (demonstration purpose)

## Future Improvements

* Train on full dataset
* Add attention mechanism
* Use Transformer models

## Example Translation

**Input (German):**
Menschen gehen auf der Straße

**Output (Model Prediction):**
A are is a . . .

**Note:** Output quality is limited due to short training and small dataset subset.

## Author

Shaida
