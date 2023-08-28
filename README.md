# Image Difference Comparator

The Image Difference Comparator is a Python script that compares two input images and highlights the differences between them. It utilizes the Structural Similarity Index (SSIM) to measure the similarity between the images and produces an output that shows the regions where the images differ.

## Features

- Comparison of two input images to detect differences.
- Calculation of the Structural Similarity Index (SSIM) between the images.
- Highlighting of differing regions using bounding boxes.
- Display of original images, difference image, and thresholded difference image.

## Usage

1. Ensure you have Python and OpenCV installed on your system.
2. Place the two images (`0.jpg` and `1.jpg`) you want to compare in the same directory as the script.
3. Run the script using the command:
   ```
   python image_difference_comparator.py
   ```
4. The script will load the two input images, calculate the SSIM, and generate visual outputs.
5. The "Original" window will display the first input image.
6. The "Modified" window will display the second input image.
7. The "Diff" window will display the different image, highlighting differing regions.
8. The "Thresh" window will display the thresholded difference image.

## Compatibility

This script requires the OpenCV library and Python installed on your system.

## Screenshots

![Screenshot](screenshot.png)
*Fig. 1: The Image Difference Comparator in action, showing original images, difference images, and thresholded difference images.*

## Contact

For any inquiries or feedback regarding the Image Difference Comparator script, please feel free to contact the developer:
Name: Morteza Hatami
Email: m.hatami@live.com
