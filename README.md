# Self-Attention, Transformers, and Pretraining
This repository contains my solutions to the coding question of assignment 4 of [CS224n](https://web.stanford.edu/class/cs224n/index.html) at Stanford. The assignment can be found [here](https://web.stanford.edu/class/cs224n/index.html#schedule). Note that the starter files are from the course and I just solved the missing parts.

The goal of this assignment is to pretrain a Transformer model on Wikipedia text data, and the finetune it for the downstream task which is predicting birthplace.

## Part (d):
In this part, we only finetune our model on the downstream task dataset. The accuracy of the trained model on validation data is **1.4%** which is expected as the model is not pretrained.

## Part (f):
In this part, we do both pretraining and finetuning. The accuracy of the trained model on validation data is **15.8%**, which satisfies the question requirements that asks for accuracy of at least 15%.

## Part (g): 
Here, we use RoPE as our positional embeddings. The accuracy of the trained model on validation data increases to **27%**.
