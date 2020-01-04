A deep learning model built using PyTorch and TorchText to classify sentiments of tweets using a subset of the sentiment140 dataset.

The model uses pre-trained GloVe embeddings to build the vocabulary and is set to not learn the emeddings for the &#60;pad&#62; token (irrelevant to determining sentiment) for improved efficiency. 
The encoder uses two layers of biLSTM and dropout for regularization.
