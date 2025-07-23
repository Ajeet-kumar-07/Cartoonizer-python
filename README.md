# Cartoonifier Python Project

This project is a simple Python application that transforms your images into cartoon-like versions using OpenCV and a graphical user interface (GUI) built with Tkinter.

## Features
- Select any image from your computer
- Apply a cartoon effect to the image
- View the transformation process step by step
- Save the cartoonified image

## Demo
When you run the application, a window will appear with a button to select an image. After selecting an image, the cartoonification process will be displayed, and you can save the final result.

## Requirements
- Python 3.x
- OpenCV (`cv2`)
- easygui
- numpy
- imageio
- matplotlib
- tkinter (usually included with Python)
- Pillow

## Installation
1. Clone or download this repository.
2. Install the required Python packages:

```bash
pip install opencv-python easygui numpy imageio matplotlib pillow
```

## Usage
Run the main script:

```bash
python cartoonifier-python-project.py
```

A window will open. Click the "Cartoonify an Image" button, select an image file, and follow the prompts to cartoonify and save your image.

## How it Works
The application:
1. Loads your selected image
2. Converts it to grayscale
3. Applies a median blur
4. Detects edges using adaptive thresholding
5. Applies a bilateral filter for smoothing
6. Combines the edges and smoothed image to create a cartoon effect
7. Displays the transformation steps
8. Lets you save the final cartoonified image

## License
This project is for educational purposes. Feel free to use and modify it. 