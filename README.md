# Recurrent Neural Networks(RNN)

### Definition:
A recurrent neural network is a type of artificial neural network commonly used in speech recognition and natural language processing. Recurrent neural networks recognize data's sequential characteristics and use patterns to predict the next likely scenario.

### Adavantages:
- Possibility of processing input of any length
- Model size not increasing with size of input
- Computation takes into account historical information
- Weights are shared across time

### Disadvantages:
- Computation being slow
- Difficulty of accessing information from a long time ago
- Cannot consider any future input for the current state

### Applications:
- Prediction problems
- Language Modelling and Generating Text
- Machine Translation
- Speech Recognition
- Generating Image Descriptions
- Video Tagging
- Text Summarization
- Call Center Analysis

### Types of RNN:

- Many to Many
   - In this we have many inputs and many outputs
   - Ex : Language translation
- Many to One
  - Many inputs but only one output
  - Ex : Sentiment analysis
- One to Many
  - Only one input(seed word) but many output
  - Ex : Music generation
- One to One
  - One input and one output
  - Traditional neural networks
