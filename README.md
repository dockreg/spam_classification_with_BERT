# CA4023_Assignment_2

This is the repository for the second assignment in CA4023 - Natural Language Technologies. This assignment contains two parts. Part one is sentiment analysis system improvements (with two  approaches) & part two is BERT fine tuning on a spam classification task. This repository contains a folder for each of the two parts within this assignment. Each section contains a jupyter notebook with all code inside.


## Part 1 - Sentiment analysis system improvements
This section takes a baseline sentiment analysis system which uses logistic regression and attempts to improve on it using two novel approaches. The two approaches are:
- Stop word removal
- Named entity recognition

## Part 2 - Spam Classification using BERT
This section involves the classfication of sms messages to predict spam. It uses BERT, created by Google in 2018 (Devlin et al. 2018). BERT is a neural network model which predicts a masked token in a sentence and also is trained in sentence similarity between two section of text to determine if they are from the same document. The model is fine tuned for this task using google colab and a sms spam dataset available from HuggingFace.

## Use of this code
To clone this repository execute the following commands:

```
git clone https://gitlab.computing.dcu.ie/dockreg2/ca4023_assignment_2.git
cd ca4023_assignment_2
```
