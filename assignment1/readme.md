# Assignment 1 Readme

## Overview

This repository contains the solutions for Assignment 1, covering various image processing tasks. The assignment is structured into multiple questions, each addressing different aspects of image manipulation and filtering. The questions are outlined below with brief explanations:

### Question 1
1. Display an 8-bit gray-level image (256x256 pixels).
2. Apply a power law transformation with gamma=0.4 to the image.
3. Add zero-mean Gaussian noise (variance=40) to the original image.
4. Apply a 5 by 5 mean filter to the noisy image.
5. Add salt and pepper noise (noise-density=0.1) to the original image.
6. Apply a 7 by 7 median filter to the salt and pepper noisy image.
7. Apply a 7 by 7 mean filter to the salt and pepper noisy image.
8. Apply a Sobel filter to the original image.

### Question 2
1. Implement a function for convolving an image with a given convolution filter.
2. Test the function on two images ("House1.jpg" and "House2.jpg") using:
   - Averaging Kernels (3x3 and 5x5).
   - Gaussian Kernels (σ=1, 2, 3).
   - Sobel Edge Operators.
   - Prewitt Edge Operators.

### Question 3
1. Apply 5 by 5 Averaging and Median filters to "Noisyimage1" and "Noisyimage2."
2. Discuss why the Median filter works better than the averaging filter for salt and pepper noise.

### Question 4
1. Compute gradient magnitude for "Q4_Image" using built-in Sobel gradients function.
2. Stretch the resulting magnitude for better visualization.
3. Compute the histogram of gradient magnitude.
4. Compute gradient orientation (angle of the gradient vector).
5. Compute the histogram of gradient orientation.

### Question 5
1. Load "walk_1.jpg" and "walk_2.jpg" images, convert them to grayscale.
2. Subtract "walk_2.jpg" from "walk_1.jpg" and analyze the result.

### Question 6
1. Apply the Canny edge detector on "Q_4.jpg" using OpenCV's Canny function.
2. Test different values of 'Threshold' and discuss the results.
