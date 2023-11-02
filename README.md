# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Neural Networks for NLP

## Recording
This lesson is intended to be given asynchronously. You may view the assigned recording [here](https://youtu.be/s99ezYFuw7k).


## Learning Objectives

*After this lesson, students will be able to:*

1. Explain why sequence modeling for NLP could be better than the previous bag-of-words models
1. Understand what a word embedding is and how they condense information into fewer dimensions
1. Follow code that carries out NLP via RNNs on sequence data, and perhaps adapt it to write code on their own

## Lesson Outline

I. **NLP with Neural Networks** 
- Recap count vectorizing for NLP problems
- Word embeddings and GloVe
- How to apply this technique to deep learning
- Some additional Keras notes

II. **Code Demo** 
- Read in IMDB review data and create Keras data structures to work with them
- Train word embeddings with Keras to predict IMDB review sentiment
- Use pre-trained word embeddings with Keras to predict IMDB review sentiment

## OPTIONAL: Resources for Practice and Learning

*For supplemental reading material on this topic, check out the following resources:*
- Andrew Ng's Coursera course on [Sequence Models](https://www.coursera.org/learn/nlp-sequence-models)
- Ava Soleimany's [video on RNNs](https://www.youtube.com/watch?v=SEnXr6v2ifU)
- [*The Unreasonable Effectiveness of Recurrent Neural Networks*](https://karpathy.github.io/2015/05/21/rnn-effectiveness/)
- A good [explanation of RNNs](https://explained.ai/rnn/index.html)
- Blog on the [Vanishing Gradient Problem](https://towardsdatascience.com/the-vanishing-gradient-problem-69bf08b15484)
- How LSTMs solve the [vanishing gradient problem](https://medium.com/datadriveninvestor/how-do-lstm-networks-solve-the-problem-of-vanishing-gradients-a6784971a577)
- A blog on the [basics of RNNs](https://medium.com/towards-artificial-intelligence/whirlwind-tour-of-rnns-a11effb7808f) 
- Francois Chollet's _Deep Learning With Python_ 2nd Edition (Find it yourself online! Or purchase it!)
