# Question-Labeling
 
## Introduction
Grouping the topic of questions is a time-consuming task. Labeling the topic of questions can be a classification problem or a clustering problem. A classification problem means we have already known all the possible topics of a given question. A clustering problem means we need to label a group of questions by their similarity. This project will provide different modeling approaches for these two problems. 

## Objectives
Problem 1: Without knowing the topics of these questions, we are going to group them by the similarity of the contents.
Problem 2: There are 5 categories of questions in total. Given a new question, we are going to label this question in one of the categories. 

## Model
Problem 1: LDA is an example of the topic model and is used to classify text in a document to a particular topic. We are able to use this clustering algorithm to find predicted existing or latent topics for each question. 
Problem 2: GloVe, a pre-trained word embedding model, is used to convert the text data into machine readable vectors in this project. Then, three machine learning models are applied for comparison, such as random forest, gaussian naive bayes, and multilayer perceptron.
