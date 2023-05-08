# Chatbot Deployment with Flask and JavaScript

## Initial Setup:
This repo currently contains the starter files.

create a virtual environment
```
$ cd chatbot
$ python3 -m venv venv
$ . venv/bin/activate
```
Install dependencies
```
$ (venv) pip install Flask torch torchvision nltk
```
Install nltk package
```
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```
Modify `intents.json` with different intents and responses for your Chatbot

Run
```
$ (venv) python train.py
```
This will dump data.pth file. And then run
the following command to test it in the console.
```
$ (venv) python chat.py
```

<!-- 
feed forward neural net with two hidden layers 

Feedforward neural networks include basic units of neural network family. The movement of data in this type of neural network is from the input layer to output layer, via present hidden layers. The output of one layer serves as the input layer with restrictions on any kind of loops in the network architecture.

nltk (natural language toolkit) is a python library to work with human language data.
PyTorch is an open source machine learning library for Python and is completely based on Torch. It is primarily used for applications such as natural language processing.  -->