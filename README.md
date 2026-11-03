# Image to Pencil Sketch Converter

Turn any photo into a pencil sketch using Python and OpenCV. Built in Google Colab in about 2 hours.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_NOTEBOOK_LINK)

## Demo

| Original | Pencil Sketch |
|----------|---------------|
| ![Original](original.jpg) | ![Sketch](sketch.png) |

## How it works
1. Converts the image to grayscale
2. Inverts the grayscale image
3. Applies a Gaussian blur to the inverted image
4. Blends it with the original using a color-dodge divide, which gives the pencil-stroke look

## Features
- Black and white graphite sketch
- Colored pencil sketch using `cv2.pencilSketch`
- Adjustable blur for bolder or softer lines
- Upload your own image in Colab and download the result

## Run it
1. Click the **Open In Colab** badge above
2. Run all cells
3. Upload an image when prompted
4. Download `sketch.png`

## Tech used
Python, OpenCV, Matplotlib, Google Colab

## Customize
- Smaller blur kernel, such as `(11, 11)`, gives darker and bolder lines
- Larger blur kernel, such as `(41, 41)`, gives softer shading
- Raise `shade_factor` in the color version for more shading

## Future ideas
- Dropdown to switch between sketch styles
- Webcam input for live sketching
- Web demo with Gradio

## Author
Diana Jazlyn S | [LinkedIn](https://linkedin.com/in/your-profile)
