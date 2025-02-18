Color Detection using OpenCV

Description

This project detects colors from an image and displays the closest color name along with its RGB values when the user double-clicks on any point in the image.

Features

Reads an image and detects colors.

Displays the closest color name based on a predefined dataset.

Shows RGB values of the selected color.

Uses OpenCV for image processing.

Implements a simple GUI for user interaction.

Installation

Prerequisites

Ensure you have Python installed along with the required libraries.

Required Libraries

Install the necessary libraries using pip:

pip install opencv-python pandas

Usage

Place the colors.csv file in the project directory.

Update the img_path variable with the path to your image file.

Run the script:

python color_detection.py

Double-click on any part of the image to see the detected color name and its RGB values.

Press Esc to exit the application.

Files

color_detection.py - Main script for color detection.

colors.csv - Dataset containing color names and RGB values.

colorpic.jpg - Sample image for testing.

How It Works

The script loads the image and reads color data from colors.csv.

When a user double-clicks on the image, the program calculates the closest color match using RGB values.

A rectangle is drawn with the detected color, and the color name along with its RGB values is displayed.

If the color is too light, the text is displayed in black for better visibility.

Example Output

After double-clicking on an image region, the output will display:

Blue R=0 G=0 B=255

License

This project is open-source and available under the MIT License.

Acknowledgments

OpenCV for image processing

Pandas for data handling
