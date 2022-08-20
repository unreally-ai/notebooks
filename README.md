# Unreally Notebooks

This repo contains all jupyter notebooks used for planing and developing the Unreally pipeline.
(Each folder represents a step in the pipeline)

The following contains brief discribtions of each notebook. If you commit one yourself, please add
some infos to this file as well.

## Step 1 - Vectors
> This folder deals with the first step of the ML pipeline: Vectorization of text & the necessesary cleaning of data.
> Also note that it contains a .zip with the datasets used

### Top5k Bow-TF
- explores the SemEval2016 A Gold dataset
- contains a custom function for cleaning text
- aims to understand how one could create a dictionary with the top 5k words of a dataset


### 5k-MultiDF Vocab
- extends the function of the previous notebook to compute one 5k vocab of multiple data frames
- more precise functions
- displays the top 5k words as a data frame

### Data2Vec
Exploring how to map, combine and vectorize the fakenewschallenge data

## Step 2 - MLP

> The second step of our pipeline: The Multi-Layer Perceptron. 

### feedforward_pytorch
A basic, working MLP using the MNIST image recognition data. This is only for reference and practice

### Feed_some_food
The current state-of-the-art notebook. This model reached about 70% accuracy. 

### hackathon
Notebook with dataloader a la best practice (work in progress)
