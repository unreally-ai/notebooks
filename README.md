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
