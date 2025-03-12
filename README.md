# Cross-Attention Side-Channel Analysis

This repository contains Demos and data on how to reproduce the results presented in "Cross-Attention for AES Mode Variation in Side-Channel Analysis."

### Dataset

This dataset provides side-channel traces collected from the CW308T-STM32F3 target board, covering five AES encryption modes: ECB, CBC, CTR, CFB, and OFB. 

The last round keys (first byte) corresponding to the data set are 3E, 5F, 61, 34, DF.


Repository structure

This repository is composed of the following folders and script:

./Dataset: the dataset (.npy format) used in the experiments.

./models: contains the final model.

. /CA-SCA_Demo.ipynb: A notebook

Each dataset is composed of the following folders and script:

- **./Data:** the dataset (.npy format) used in the experiments. 
- **./models**: contains the pre-trained model, fine-tuned model, etc.
- **..._CDPA_Demo.ipynb**: the notebook file that contains both codes and outputs. This notebook demonstrates how to load a dataset, how to pre-process the data, how to fine-tune a network, how to evaluate the pre-trained and fine-tuned models, etc. 


