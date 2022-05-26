# Callback_demo

## A short Intro

This is a demo code made for Prof.CHEN Yingcong's research group students. It serves as a training callback template for students to collaborate. For demo video recording, please see Notion page for details. 

Part of the code is taken from Fastai 2019 part 2 course, where I was invited as an international fellow. 

## A breakdown to the demo notebook

1. Data, MNIST original, data are length 784 vectors
2. Model, a tiny MLP with 2 linear layer with a relu between them
3. Loss, cross entropy

Please scroll down the demo notebook, where you will see implemented example callbacks, they are SetUpCallback, LoopControlCallback, LogCallback and more...

To understand the notebook:

1. The Learner_Nocallback class shows a basic training loop with no cbs
2. The NewLeaner class shows a training loop with callback and event (exceptions) controlled loop

