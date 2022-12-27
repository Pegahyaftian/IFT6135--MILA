# IFT6135--MILA
Assignments for the course IFT6135 (representation learning) at MILA.


## Assignment 2
Neural machine translation task on the [Multi30k](https://github.com/multi30k/datasetAssignment) dataset, between English and French.
The dataset contains pairs of sentences in English and French. Sequential language models do next-word prediction: they predict tokens in a sequence one at a time, with
each prediction based on all the previous elements of the sequence. A trained sequential language model can then be used to generate new sequences of text, by making each prediction conditioned on the past predictions. Encoder-decoder models that process the sentence from the source language and translate it to the target language.\\
The implemented models are: 1) Encoder-Decoder GRU model, 2) Encoder-Decoder transformer model.
