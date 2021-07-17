# Aplogies WIP, Will finish it by 7/19

## Referring to:

### [Glove Site](https://nlp.stanford.edu/projects/glove/)
This provides the glove embeddings of various sizes and dimensions.

  - We will focus on Wikipedia 2014 + Gigaword 5 (6B tokens, 400K vocab, uncased, 50d, 100d, 200d, & 300d vectors, 822 MB download): [glove.6B.zip](https://nlp.stanford.edu/data/glove.6B.zip)
  - Even in this zip, there are various files, here the numbers represent the size of the vectors in the vocabulary.
  - In a 50 dimensional vocabulary tokens are represented as 50-dimensional vectors, in a 100-dimensional vocabulary tokens are represented as 100-dimensional vectors, etc.
  - I choose the 50d pretrained embedding to start with.

### [Medium Link](https://medium.com/@martinpella/how-to-use-pre-trained-word-embeddings-in-pytorch-71ca59249f76)
This medium link explains how to use Pre-trained Word Embeddings in PyTorch.

### [Sean's Notebook Exploring Word Vectors with GloVe](https://github.com/spro/practical-pytorch/blob/master/glove-word-vectors/glove-word-vectors.ipynb)
Here the same author explains how to use Glove Word Vectors.

### We just have to change the embedding vector and validate - WIP
