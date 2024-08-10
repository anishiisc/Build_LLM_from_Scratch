# Build_LLM_from_Scratch

This repo is a WIP towards developing a series of tutorial notebooks towards buidling a LLM from scratch 
The primary reference text for this Tutorial series is 
https://www.manning.com/books/build-a-large-language-model-from-scratch


## The Repo contains the following notebooks 

###  LLM_1_Tokeniser
In this notebook we develop step by a step a tokenizer class. The text we will tokenize for LLM training is a short story by Edith Wharton called The Verdict, which has been released into the public domain and is thus permitted to be used for LLM training tasks. The text is available on Wikisource at https://en.wikisource.org/wiki/The_Verdict,
A notebook based tutorial series on buildling a LLM from scratch 


###  LLM_2_Byte Pair Encoding
In the first notebook, we discussed how to develop a Word Tokenizer step by step. In this notebook we will demonstrate The next step before we can finally create the embeddings for the LLM, which  is to generate the input-target pairs required for training an LLM.


###  LLM_3_Data Loader
In this notebook we explain the concept of Dataset Class and Data Loader in pytorch. We also explain with a series of examples how the X data and traget sequence of tokens are generated for creating a next word predictor 


###  LLM_4 Embeddings 
In this notebooks ; we explain the concept of word embeddings and how both tokens and token positions are accounted for through embeddings as input for the train process , through initial randomly generated embedding weights.

