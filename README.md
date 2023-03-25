[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-8d59dc4de5201274e310e4c54b9627a8934c3b88527886e3b421487c677d23eb.svg)](https://classroom.github.com/a/S8i0Ljb1)
# Challenge Problem 5

## Deadline: March 24, 2023 by midnight

Note: While high-level discussion is allowed and encouraged for the challenge problems, these problems should be completed and submitted individually.

### Description

Run through the guide at [RNN guide](https://www.tensorflow.org/guide/keras/rnn). Then, answer the following questions.

### Part 1: Keras

1.   Give 1-2 sentence description of keras.

Keras is a tool that one can use to interact with complex AI in a relatively easy way. This specific use of Keras allows us to run a Recurrent Neural Network (RNN) on data that we choose.

2.   Give a short explanation of the following:

- `Embedding`
-  `Dropout` 

Embedding is basically mapping the different values of the data from integers to vectors before processing them into a different layer.

Dropout pretty much just removes some data points during training and ignores them, so they're not able to affect other nodes afterwards throughout the training process.

### Part 2: Unidirectional vs Bidirectional

1.   Give 2-3 sentence explanation of how bidirectional RNNs are different from unidirectional RNNs.

Bidirectional RNNs differ from normal RNNs because they go through the data from end to start as well as start to end. Including backwards analysis can be especially useful when doing things like language processing because it can be important to know what words come after a given word instead of just knowing what's before. Normal RNNs don't have that same level of analysis on the data from all directions, which to be fair is sometimes unnecessary.

### Part 3: Add code

1.   Include the code from "Recurrent Neural Networks (RNN) with Keras" guide that you ran (must show output) as a Google Colab notebook in your challenge 5 repository.
