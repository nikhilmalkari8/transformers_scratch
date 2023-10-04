# Transformers-from-scratch

Welcome to the "Transformers-from-scratch" repository! This repository contains code for implementing Transformers from scratch in PyTorch. The primary purpose of this code is educational, aiming to help you understand the various components involved in the Transformers architecture.

## Getting Started

To run the scripts on your local machine, follow these steps:

### Clone the Repository

First, clone the repository to your local machine using the following command:

```bash
## Getting Started

To run the scripts on your local machine, follow these steps:

### Clone the Repository

First, clone the repository to your local machine using the following command:

```bash
$ git clone https://github.com/hrajgarhia/Transformers-from-scratch.git
$ cd Transformers-from-scratch


### Running on your machine

To run the scripts on your own machine, first clone the repository and navigate to it:

```bash
$ git clone https://github.com/hrajgarhia/Transformers-from-scratch.git
$ cd Transformers-from-scratch
```

Next, run the following command to create a `conda` virtual environment that contains all the libraries needed to run the notebooks:

```bash
$ conda env create -f environment.yml
```


Once you've installed the dependencies, you can activate the `conda` environment as follows:

```bash
$ conda activate tfs
```


Once you've activated the `tfs conda` environment, you can start training the transformers for machine translation tasks as follows:

```bash
$ python train.py
```

Repository Structure

This repository is organized as follows:

data/: Contains data files required for training and evaluation.
notebooks/: Jupyter notebooks with detailed explanations of the code.
src/: Source code for implementing Transformers from scratch.
train.py: The main script to train Transformers.

Acknowledgments

This repository was inspired by the original Transformers paper "Attention Is All You Need" by Vaswani et al. If you find this code helpful, consider citing the paper.

Enjoy exploring Transformers from scratch and happy learning!