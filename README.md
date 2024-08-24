# Convolutional Neural Networks

## Overview
The purpose of this Jupyter Notebook is to explore and implement a Convolutional Neural Network (CNN) using the `numpy` library. It also covers the fundamental operations necessary for understanding and building CNNs such as zero padding, convolution at a single position, and forward passes for convolution and pooling layers.

## Features
- **Zero Padding:** Add zeros to the perimeter of an image matrix, preparing it for the convolution process without losing edge information.
- **Single Position Convolution:** Perform convolutions at a single matrix position to understand the filtering process.
- **Convolution Layer:** Implement a complete forward pass through a convolution layer.
- **Pooling Layer:** Demonstrate the forward pass through a pooling layer, reducing spatial dimensions while retaining important features.

## Usage
Run each cell sequentially to observe how CNN operations are implemented, as well as how they affect the input data. Modify parameters and inputs to experiment with different behaviors and results.

## Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab
- Python libraries such as `numpy`

## Input
The input to each operation (e.g., zero padding, convolution) is a matrix, or a set of matrices, representing image data or feature maps.

## Output
Outputs are processed matrices showcasing the results of each CNN operation, such as the output of a convolution or a pooling layer.

## Notes
 - Ensure that numpy is installed and up-to-date to avoid any compatibility issues.
- This notebook is basic in order to demonstrate the workings of convolutional neural networks and requires modifications for production use.