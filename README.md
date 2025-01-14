# my-deep-learnings

Repository to keep track of my exploration, experiments and learnings.

- Delving into the theory : Original paper(s) (if available), relevant cited works and blogs.
- Code implementation of the ideas.

## Papers 📑

A collection of seminal research papers are collected under `resources/papers`.

## Computer Vision 👁️

### Architectures

1. Convolutional Neural Network (CNN)
2. Residual Networks (ResNets)
3. Mask RCNN
4. U-Net

> From coarse grained to fine grained CV tasks explored : 

1. Image Classification
  * Single-label 
  * Multi-label
2. Object Detection (and Localization)
3. Image Segmentation 
  * Semantic Segmentation
  * Instance Segmentation
5. Image Regression - predicting a continuous value for the target for e.g. detecting the human pose involves outputting the location (x,y) of skeletal keypoints in a given frame.

Classification/segmentation is most common in vision based applications.

## Natural Language Processing 📜

### Architectures

1. Recurrent Neural Network (RNN)
2. Gated Recurrent Unit (GRU)
3. Long Short-Term Memory (LSTM)

> NLP tasks :

1. Text classification
  * Sentiment Analysis
2. Topic Modeling 

Transfer learning in NLP : Fine tuning a pretrained language model (e.g. WikiText 103) on a domain specific corpus (i.e. Yelp, IMDb) and then using the encodings to train a text classifier.

## Unsupervised/Self supervised/Generative Deep Learning

1. Autoencoders (AE)
  * Stacked AE
  * Denoising AE
  * Variational AE

2. Generative Adversarial Networks (GANs)

## Core/Foundational from scratch

1. Linear Algebra
2. Broadcasting
3. Matrix/Tensor Multiplication

## Frameworks used :

1. PyTorch
2. fastai

## Enviroment :

1. Google Colab
2. Jupyter Notebook
3. Python 3

## Resources

1. https://www.fast.ai/
2. http://neuralnetworksanddeeplearning.com/
3. https://www.deeplearningbook.org/
