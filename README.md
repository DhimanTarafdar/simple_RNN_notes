Simple RNN Notes

A personalized recap and learning summary from my notebook on Simple Recurrent Neural Network (RNN).

What I Learned

In this notebook, I studied the basic concepts of Recurrent Neural Networks (RNNs) and why they are important for handling sequential data.

I explored:

Why traditional Neural Networks like ANN and CNN are not enough for sequence-based problems
What sequential data is
How RNN remembers previous information using Hidden State
How RNN processes data step-by-step through time
Different RNN architectures
Trainable parameter calculation
Input/output shapes in PyTorch
Basic intuition of Backpropagation Through Time (BPTT)
Main Topics Covered
1. Introduction to RNN
What is RNN
Why RNN was introduced
Meaning of “Recurrent”
2. Sequential Data

Examples of sequential data:

Text
Time Series
Audio / Speech
Video
DNA sequence
3. ANN vs RNN

I compared:

Memory handling
Input processing
Sequence understanding
Weight sharing
4. Text Representation

Learned about:

One-Hot Encoding
Sparse vector problem
Word Embedding
5. Hidden State & Memory

Understood how RNN stores previous context using hidden states.

6. RNN Architecture

Studied:

Input (xₜ)
Hidden State (hₜ)
Output (yₜ)
Weight matrices
tanh activation
7. Unfolded RNN

Learned how RNN works through multiple time steps.

8. Types of RNN
Many-to-One
One-to-Many
Many-to-Many
Encoder-Decoder
9. Trainable Parameters

Calculated parameters manually and verified them using PyTorch.

10. PyTorch Implementation

Implemented a simple RNN model using:

nn.RNN
Linear Layer
Sigmoid Activation
