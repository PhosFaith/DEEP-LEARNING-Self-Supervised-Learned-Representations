# DEEP LEARNING : Self-supervised learned representations 

This repository contains the solution for the Self-supervised learned representations lab. The lab focuses on analyzing and using representations learned by pre-trained self-supervised models for various NLP tasks, including word analogies, cross-lingual word embedding mapping, visualization, and building a simple chatbot. It also explores image embeddings using DINO.

## Problem 1: Word embeddings

This section covers tasks related to word embeddings, including:

* Evaluating word analogies.
* Performing cross-lingual word embedding mapping using Procrustes analysis.
* Visualizing word embeddings using PCA and t-SNE.

## Problem 2: Sentence embeddings

This section focuses on building a simple chatbot using different sentence embedding methods:

* Implementing a k-nearest neighbor (KNN) based chatbot.
* Representing sentences by averaging word2vec embeddings.
* Representing sentences using BERT.
* Incorporating context in chatbot responses.
* Performing basic data cleaning based on embeddings.

## Problem 3: Image embeddings

This section explores image embeddings using DINO:

* Visualizing attention maps for semantic segmentation.
* Analyzing t-SNE plots of image embeddings.
* Evaluating KNN and linear classifiers built on top of DINO embeddings.

## Requirements

To run the notebooks, you will need the following libraries:

* `numpy`
* `collections`
* `pickle`
* `scipy`
* `tabulate`
* `matplotlib`
* `sklearn`
* `pprint`
* `codecs`
* `nltk`
* `tqdm`
* `gdown`
* `httpimport`
* `transformers` (huggingface)
* `termcolor`
* `torch`
* `torchvision`
* `PIL`

You can install the necessary packages using pip:

```bash
pip install numpy collections pickle scipy tabulate matplotlib sklearn pprint codecs nltk tqdm gdown httpimport transformers termcolor torch torchvision Pillow
