# Neural Style Transfer
A Python implementation of Neural Style Transfer using TensorFlow and TensorFlow Hub. This project allows you to apply the artistic style of one image to another image.
Neural Style Transfer is an AI technique that combines two images - a content image and a style image - to create a new image that maintains the basic structure of the content image while adopting the artistic style of the style image. For example, it can make a regular photograph look like it was painted by Van Gogh or drawn in a comic book style. This is achieved using deep neural networks that separate and recombine the content features (like shapes and objects) from one image with the style features (like colors, textures, and brush strokes) from another. The technique was first introduced in 2015 and has since become a popular tool for creating artistic transformations of photographs and exploring the intersection of AI and art.
# Overview
Neural Style Transfer is a technique that takes two images — a "content" image and a "style reference" image (such as a famous painting) — and blends them together so the output image looks like the content image, but "painted" in the style of the style reference image.

# Requirements
1. Python 3.7+
2. TensorFlow
3. TensorFlow Hub
4. Pillow
5. NumPy
6. Matplotlib

# Installation
`pip install tensorflow tensorflow-hub Pillow numpy matplotlib`

# How It Works
The implementation consists of three main components:

## Image Processing
1. Loads and preprocesses images
2. Resizes images while maintaining aspect ratio
3. Normalizes pixel values

## Style Transfer
1. Uses a pre-trained model from TensorFlow Hub
2. Applies the style of one image to the content of another
3. Generates a stylized output image

## Visualization
1. Displays the original content image
2. Shows the style reference image
3. Presents the final stylized result


# Features
- Easy-to-use interface
- Support for various image formats
- Automatic image preprocessing
- Visual comparison of results


## The program takes:
- A content image (e.g., a photograph)
- A style image (e.g., a painting)
- **And produces:** A stylized image combining both

![download (1)](https://github.com/user-attachments/assets/df6db2bb-55ca-465a-8de0-ea91cec6b4b7)
