# Neural Style Transfer using VGG19

This project demonstrates neural style transfer, a technique for applying the artistic style of one image to the content of another image using the VGG19 neural network.

## Overview

In NST, the VGG19 network is used to extract features from two images: a content image and a style image. The VGG19 network, trained on a vast dataset, captures high-level content and style features across multiple layers. By minimizing a loss function that combines content loss and style loss, the algorithm iteratively updates a generated image to resemble the content of the first image with the style of the second.
## Requirements

- Python 3.x
- PyTorch
- torchvision
- PIL (Python Imaging Library)
- matplotlib

## References
- A Neural Algorithm of Artistic Style
- PyTorch Neural Transfer Tutorial
