# Cross-Attention Side-Channel Analysis

This repository contains Demos and data on how to reproduce the results presented in "Cross-Attention for AES Mode Variation in Side-Channel Analysis."

### Dataset

This dataset provides side-channel traces collected from the CW308T-STM32F3 target board, covering five AES encryption modes: ECB, CBC, CTR, CFB, and OFB. 
<div align="center">
    <img src="https://github.com/hfl110529/CA-SCA/raw/main/figures/STM32F3.png" alt="Editor" width="240">
    <img src="https://github.com/hfl110529/CA-SCA/raw/main/figures/setups.jpg" alt="Editor" width="400">
    <img src="https://github.com/hfl110529/CA-SCA/raw/main/figures/AES encryption mode.png" alt="Editor" width="640">
</div>


The last round keys (first byte) corresponding to the data set are 3E, 5F, EA, 34, DF.


### Repository structure

This repository is composed of the following folders and script:

**./Dataset:** the dataset (.npy format) used in the experiments.

**./models_CA:** contains the final model.

**. /CA-SCA_Demo.ipynb:** A notebook file containing code and output. The notebook demonstrates how to load the dataset, how to preprocess the data, how to perform cross-attention training, and how to evaluate the model.





