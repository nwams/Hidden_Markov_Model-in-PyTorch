# Build a Hidden Markov Model in PyTorch
Use PyTorch to Build a Hidden Markov Model for both Weather Prediction and whether a person is Healthy or Feverish.

**PyTorch** is a deep learning neural networks package for Python [[Youtube - PyTorch Explained](https://www.youtube.com/watch?v=iTKbyFh-7GM)].

This is a practical project for learning Probabilistic Graphical Models (PGM). It implements the **Viterbi**, **Forward-Backward** and the **Baum Welch** algorithms.

I added my own personal enhancements (like clearer code documentation) and modifications to [this original project](https://nbviewer.jupyter.org/github/TreB1eN/HiddenMarkovModel_Pytorch/blob/master/HiddenMarkovModel.ipynb) put together by [TreB1eN](https://github.com/TreB1eN).

## Hidden Markov Model (HMM)
A Markov chain is useful when we need to compute a probability for a sequence of observable events. In many cases, however, the events we are interested in are hidden: we don’t observe them directly. For example we don’t normally observe part-of-speech tags in a text. Rather, we see words, and must infer the tags from the word sequence. [[pg 2, Dan Jurafsky, Stanford](https://web.stanford.edu/~jurafsky/slp3/A.pdf)]

In HMM the sequences are hidden because it is not possible to tell the state merely by the output symbol.
