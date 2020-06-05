### Project Overview

 Haptik is one of the world's largest conversational AI platforms. It is a personal assistant mobile app, powered by a combination of artificial intelligence and human assistance. It has its domain in multiple fields including customer support, feedback, order status and live chat.

We have with us the dataset of Haptik containing the messages it receives from the customers and which topic(class) the messages refer to.

We need to create a model predicting which class a particular message belongs to using NLP. We will also try to use techniques like LSA (Latent Semantic Analysis) and LDA (Latent Dirichlet Allocation) to assign topics to new messages.


### Learnings from the project

 Solving it will help us to learn the following skills:

Text preprocessing techniques like tokenization, vectorization, etc.

Implementation of Logistic Regression, Naive Bayes and Linear SVM.

Topic modelling with LSA (Latent Semantic Analysis) and LDA (Latent Dirichlet Allocation)

Usage of coherence score to determine the optimum number of topics


### Approach taken to solve the problem

 To solve the problem we first used text preprocessing techniques tokenization and vectorization to make data in a machine-understandable format then we tried to use different algorithms for classification of messages. After training and testing of the model, we did the topic modelling using LSA and LDA.


### Challenges faced

 As the categories do not exist in the main dataset so the main challenge was to define the categories. To solve this challenge, We used a function which created categories according to the text using the other features or columns of the dataset.


