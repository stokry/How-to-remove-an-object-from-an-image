# How-to-remove-an-object-from-an-image
A sweet algorithm with which you can remove objects from the picture. 

We will be using modified Template Matching approach.
We will load the template, convert to grayscale, perform canny edge detection, after that we do load the original image, convert to grayscale
Continuously rescale the image, apply template matching using edges, and keep track of the correlation coefficient (higher value means better match)
Find coordinates of best-fit bounding box then erase unwanted ROI.
