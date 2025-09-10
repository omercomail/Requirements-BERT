
# An assessment of the impact of Model Components and Data Set Size on BERT Fine-Tuning for Software Requirements Classification.




## Authors

- Safaa Eltahier, Omer Dawood, and Imtithal A. Saeed 

## Overview

	
This repository includes python code for requirements classification based on BERT fine tuning, with two significance:
- Development and performance evaluation of BERT fine-tuning for Software Requirements Classification (SRC), with a focus on the impact of key hyperparameters and dataset size on model performance.
- A detailed ablation study to check how individual hyperparameters work, helping us find the best settings for strong and efficient performance. 


## Dataset

Two datasets are utilized for the experiments:
- PROMISE- NFR data set : The PROMISE NFRs software requirements dataset  is one of the most frequently used datasets. It maintained by the School of Information and Engineering at the University of Ottawa, Canada, since 2005. It  consists of 625 software requirements.
- PURE data set: PURE (Public  REquirements dataset), a collection of 79 publicly accessible natural language requirements documents sourced from the Web. The dataset comprises 34,268 sentences and is suitable for various natural language processing tasks common in RE, 

## Requirements
Set up the environment, install the following libraries:
- pip install tensorflow==2.12 keras==2.12 transformers==4.27.4 nltk seaborn scikit-learn nltk  numpy pandas matplotlib
- import nltk
- nltk.download('omw-1.4')
- import nltk
- nltk.download('all')

## Model Architecture
For classification tasks, BERT's input consists of token, segment, and position embeddings, which are combined for each token in the sequence. The model employs multiple layers of bidirectional transformer encoders with self-attention mechanisms and feed-forward networks to understand contextual information from both directions. 
Architecture Includes:
- Text preprocessing and tokenization using BERT.
- Fine-tuning of BERT for classification task.
- Hyperparameter Tuning.


## References
This source code forked and edited from:

https://github.com/engrsoonhtaj/BERT-for-RE/blob/main/Productivity%20ACD.ipynb