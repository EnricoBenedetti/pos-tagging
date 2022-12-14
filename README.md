# POS tagging implementation and analysis of performance on four RNN architectures

This repository contains the code and analysis for a study on the performance of different recurrent neural network (RNN) architectures for part-of-speech (POS) tagging. The four RNN architectures compared in this study are:

- Baseline: Bidirectional LSTM (BiLSTM) + Fully connected (FC) Layer
- GRU: Bidirectional GRU (BiGRU) + Fully connected (FC) Layer
- additional-LSTM: Bidirectional LSTM (BiLSTM) x2 + Fully connected (FC) Layer
- additional-FC: Bidirectional LSTM (BiLSTM) + Fully connected (FC) Layer x2

The code is implemented in Python using the PyTorch deep learning framework, and hyper-parameter tuning with the Ray Tune library.

## Results

The results of the study can be found in the `pos_tagging_experiments.ipynb` Jupyter notebook, and a summary in paper form in the `report.pdf` file.


### Acknowledgements
To my teammates for this project, Stefano Fantazzini (stefano.fantazzini@studio.unibo.it), Irene Gentilini (irene.gentilini2@studio.unibo.it) and Elisa Ancarani (elisa.ancarani4@studio.unibo.it), thanks for the coding and writing together.
