# Neural Style Transfer using VGG19

This project demonstrates neural style transfer, a technique for applying the artistic style of one image to the content of another image using the VGG19 neural network.

## Overview

Neural style transfer is an optimization technique used to take three images, a content image, a style reference image, and the input image you want to transform. The goal is to manipulate the input image so that it matches the content of the content image and the style of the style reference image.

This project uses a pre-trained VGG19 model from PyTorch's `torchvision.models` to perform the style transfer.

## Requirements

- Python 3.x
- PyTorch
- torchvision
- PIL (Python Imaging Library)
- matplotlib

You can install the required packages using pip:

```bash
pip install torch torchvision pillow matplotlib

