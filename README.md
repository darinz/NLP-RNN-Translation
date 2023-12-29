# NLP: Recurrent Neural Network (RNN) Seq2Seq Machine Translation with Attention

In this tutorial we aim to guide you through building and training your own RNN for Machine Translation with Attention, starting from scratch. We'll break down the process into bite-sized steps, focusing on the essential building blocks of Natural Language Processing and data preprocessing. By crafting each component yourself, you'll gain a deep understanding of how RNNs handle text data and perform machine translation.

## Recommended Preparation

Before starting this tutorial it is recommended that you have installed [PyTorch](https://pytorch.org/) or use [Google Colab](https://colab.research.google.com/?utm_source=scs-index), and have a basic understanding of [Python programming language](https://www.python.org/doc/) and [Tensors](https://pytorch.org/tutorials/beginner/basics/tensorqs_tutorial.html):

### Google Colab

For tips on running tutorial notebooks in Google Colab, see [Colab Pytorch Tutorial](https://pytorch.org/tutorials/beginner/colab)

### Conda Environment Setup

Use the first command to create new independent environment for the project. Or use the other two commands to remove or update the Conda environment.

```shell
# To create a conda environment.
conda env create -f environment.yml

# To remove a conda environment.
conda remove --name nlp --all

# To update a conda environment when some new libraries are added.
conda env update -f environment.yml --prune
```
Then, install [PyTorch](https://pytorch.org/).

## Recurrent Neural Networks Resources

It would also be useful to know about Sequence to Sequence networks and
how they work:

-  [Learning Phrase Representations using RNN Encoder-Decoder for
   Statistical Machine Translation](https://arxiv.org/abs/1406.1078)
-  [Sequence to Sequence Learning with Neural
   Networks](https://arxiv.org/abs/1409.3215)
-  [Neural Machine Translation by Jointly Learning to Align and
   Translate](https://arxiv.org/abs/1409.0473)
-  [A Neural Conversational Model](https://arxiv.org/abs/1506.05869)

### Citation

```bibtex

```
