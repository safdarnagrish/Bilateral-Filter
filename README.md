Bilateral Filter Application

University Project

This repository contains a simple Python project that demonstrates the application of a bilateral filter on an image using the OpenCV library. The project is part of a university assignment aimed at exploring image processing techniques.

Project Overview

The bilateral filter is a non-linear, edge-preserving, and noise-reducing filter useful in a variety of image processing applications. Unlike other filters, it smooths images while preserving sharp edges, making it particularly effective in removing noise while retaining important details.

This project reads an input image, applies the bilateral filter, and displays the original and filtered images side by side.

Features

Input Image: The project reads an image from the file system.
Bilateral Filter: Applies a bilateral filter to reduce noise while preserving edges.
Visualization: Uses Matplotlib to display the original and filtered images.
Getting Started
Prerequisites
Make sure you have the following packages installed:

Python 3.x

OpenCV (cv2)

NumPy

Matplotlib

You can install the required packages using pip:

bash

Copy code
pip install opencv-python numpy matplotlib
Running the Project
Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/bilateral-filter-project.git
cd bilateral-filter-project
Place your input image (e.g., girl.jpg) in the project directory.


Run the Python script:


bash
Copy code
python bilateral_filter.py
The script will display the original and filtered images side by side.


Project Structure

bilateral_filter.py: The main script that reads the image, applies the bilateral filter, and displays the results.
README.md: This file, providing an overview of the project and instructions for use.
girl.jpg: The input image used for demonstration (you can replace this with your own image).

Example Output

After running the script, you should see a window displaying two images:

Original Image: The unfiltered input image.

Filtered Image: The result after applying the bilateral filter.
Usage
This project can be used as a starting point for more advanced image processing tasks. The parameters of the bilateral filter (d, sigmaColor, sigmaSpace) can be adjusted to see their effect on different images.

License
This project is open-source and available under the MIT License. Feel free to modify and use the code as needed.

Acknowledgments
This project was developed as part of a university course on Digital Image Processing.
The bilateral filter is a well-known technique in image processing and has been implemented using OpenCV in this project.
