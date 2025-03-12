# Cross-Attention Side-Channel Analysis

This repository contains Demos and data on how to reproduce the results presented in "Cross-Attention for AES Mode Variation in Side-Channel Analysis."

### Dataset

This dataset provides side-channel traces collected from the CW308T-STM32F3 target board, covering five AES encryption modes: ECB, CBC, CTR, CFB, and OFB. 

The last round keys (first byte) corresponding to the data set are 3E, 5F, 61, 34, DF.


**Repository structure**

This repository is composed of the following folders and script:

**./Dataset:** the dataset (.npy format) used in the experiments.

**./models:** contains the final model.

**. /CA-SCA_Demo.ipynb:** A notebook file containing code and output. The notebook demonstrates how to load the dataset, how to preprocess the data, how to perform cross-attention training, and how to evaluate the model.





