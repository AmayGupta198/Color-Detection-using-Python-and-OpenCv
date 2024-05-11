# Color-Detection-using-Python-and-OpenCv

In this project, I developed a color detection tool using Python and OpenCV. The program allows users to interactively select a color from an image by double-clicking on it. Upon selection, the program identifies the closest matching color from a pre-defined dataset and displays its name along with its RGB values. This tool provides a convenient way to analyze and identify colors within images, which can be useful in various applications such as image processing, computer vision, and graphic design.

# Objective

1. Develop a color detection tool using Python and OpenCV.
2. Enable users to interactively select colors from images by double-clicking on them.
3. Identify the closest matching color from a pre-defined dataset.
4. Display the name and RGB values of the selected color in real-time.

# Methodology

1. Library Import: Import necessary libraries including OpenCV and pandas.
2. Image Loading: Load the image to be analyzed.
3. Global Variables: Declare variables to store clicked position and color values.
4. Color Data Reading: Read color data from a CSV file.
5. Color Detection Functions: Implement functions to calculate closest matching color and handle mouse events.
6. Main Loop: Create a window to display the image and continuously check for mouse events.
7. Color Selection: When a double click event occurs, draw a rectangle around the selected color and display its name and RGB values.
8. User Interaction: Continuously update the display and wait for user input (like pressing 'esc' to exit).
9. Cleanup: Close all OpenCV windows after exiting the loop.







