# MNIST Digit Recognition Flask App

This web app allows users to upload a handwritten digit image. These images are passed to a pre-trained ONNX model. The predicted digit and confidence values are shown with a bar chart. If the image is not a number rather a pucture, it would show the probability of the numbers.

## Features

- Upload any image or choose a sample MNIST image
- Automatically resizes to 28x28 and converts to grayscale
- Uses ONNX for prediction
- Displays prediction result and chart.js bar plot

## Run Instructions

```bash
pip install flask onnxruntime pillow numpy
python app.py
