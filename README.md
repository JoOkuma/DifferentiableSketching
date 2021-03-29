<div align="center">
  
# Differentiable Sketching

This repository contains the __official__ implementation of the paper ['Differentiable Drawing and Sketching.'](https://arxiv.org/abs/XXX)


<p align="center">
  <a href="https://arxiv.org/abs/XXX">ArXiv</a> •
  <a href="https://paperswithcode.com/paper/differentiable-drawing-and-sketching">Papers With Code</a> •
  <a href="#about">About</a> •
  <a href="#usage">Usage</a> •
  <a href="#experiments">Experiments</a> 
</p>

<!-- <a href="https://colab.research.google.com/github/ecs-vlc/fmix/blob/master/notebooks/example_masks.ipynb">
<img src="http://www.pytorchbearer.org/assets/img/colab_logo.png" height="28">

Dive in with our example notebook in Colab!
 -->  
</a>

</div>

## About

This is a bottom-up relaxed differentiable relaxation of point/line/curve rasterisation and sketch generation implemented entirely as GPU-accelerated tensor operations in [PyTorch](http://pytorch.org). We relax the act of rasterising primitive objects such that there is a gradient with respect to every pixel in the image to the primitive's parameters. Rasterisations of primitives can then be composed in different ways (so long as they are differentiable) to achieve a resultant output which can be optimised. 

We demonstrate that it is possible to perform gradient descent directly through the rasteriser to make the generated image match a target imaeg according to some loss (which could be a simple function, or even a complex neural network). We also demonstrate the use of the rasteriser in auto-encoder models that learn to both produce reconstructions whilst simultaneously learning the actual parameters of underlying vector primitives, and thus differentiably perform [automatic image tracing (aka autotracing)](https://en.wikipedia.org/wiki/Image_tracing).

## Usage

### Installation

### Demonstration Notebooks

### Tools

#### Image Optimisation

## Experiments

### Optimisation

### Auto-encoders




