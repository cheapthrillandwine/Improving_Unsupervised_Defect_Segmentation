# Improving_Unsupervised_Defect_Segmentation

This is Keras code from "Improving Unsupervised Defect Segmentation by Applying Structural Similarity to Autoencoders".
https://arxiv.org/abs/1807.02011
I tried for my computer vision research. 
That's is amazing method for unsupervised defect segmentation using AutoEncoder with SSIM.

# Usage
## 0. Install Library

`keras >= 2.0`
`tensorflow >= 1.6`
`scikit-learn`
`PIL`
`matplotlib`

## 1. Use AutoEncoder

You can use your images with AutoEncoder.ipynb.
Please set your Image Path and automatically be resized on this code 128*128*1.

## 2. Use SSIM

Next time, you can compare Inpue Image and Decoded Image.

If you use SSIM method, you have to `pip install SSIM-PIL`.
