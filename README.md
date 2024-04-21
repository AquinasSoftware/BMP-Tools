# BMP-Tools
A small collection of tools to alter BMP files

## About the Project
The purpose of this project was to demonstrate the fundamentals of augmented reality. The technology uses constant alteration of image and video data, either by deconstructing the base image and inserting special effects and/or overlaying a second image/video feed. Therefore, if one can alter images on a low level, it sets the foundation for these advanced techniques.

The program demonstrates this via 3 proofs of concept: Horizontal flipping, Grayscaling and Coloration. Obviously, these techniques are already common and can be done in almost any higher language. But the idea behind this project was to showcase it running on synthesized hardware.

## How to Use
These Verilog modules were created and simulated in ModelSim. They accept ``in.bmp`` as an input file. It must be a 24-bit BitMap image with no compression or color space data.

## Special Thanks
Thank you to [@dampdigits](https://www.github.com/dampdigits) for providing a template with his image-flipper program. You can find it here:
https://github.com/dampdigits/image-flipper
