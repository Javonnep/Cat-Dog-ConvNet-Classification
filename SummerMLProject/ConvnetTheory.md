# Convolutional Neural Networks

A type of neural network commonly used to detect/classify images

## Filters

1. An image is stored as a matrix with each pixel(number) having an activation
2. For each pixel, we take an NxN matrix and find the dot product 
3. Using the values we obtain we now have a completely new matrix

 The NxN matrix is the filter.

## Convolutional Layers

**MaxPooling** 

- 

**ZeroPadding**

When we convolve using a filter we lose (n-1) pixels from 2 edges of the image.

To avoid losing these pixels we add a layer of Zero's around the edge of the image