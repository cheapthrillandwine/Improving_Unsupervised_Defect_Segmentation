# Improving_Unsupervised_Defect_Segmentation

This is Keras code from "Improving Unsupervised Defect Segmentation by Applying Structural Similarity to Autoencoders".<br>
https://arxiv.org/abs/1807.02011 <br>
I tried for my computer vision research. <br>
That's is amazing method for unsupervised defect segmentation using AutoEncoder with SSIM. <br>

# Usage
## 0. Install Library

`keras >= 2.0` <br>
`tensorflow >= 1.6` <br>
`scikit-learn` <br>
`PIL` <br>
`matplotlib` <br>

## 1. Use AutoEncoder

You can use your images with AutoEncoder.ipynb. <br>
Please set your Image Path and automatically be resized on this code 128×128×1. <br>
*minimum 10 images required*

## 2. Use SSIM

Next time, you can compare Inpue Image and Decoded Image.<br>

If you use SSIM method, you have to `pip install SSIM-PIL`.
