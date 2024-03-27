# Global Thresholding using Otsu's Method

This repository contains Python code that implements global thresholding using Otsu's method in computer vision. Global thresholding is a technique used to segment foreground objects from the background in an image based on a single threshold value.

## About
Global thresholding is a simple yet effective technique for image segmentation. Otsu's method is a widely used algorithm to automatically determine the optimal threshold value based on the image histogram. This implementation utilizes OpenCV and NumPy libraries to calculate the image histogram, find the optimal threshold, and apply binary thresholding.

## Requirements
- Python 3.12
- OpenCV (cv2): 
- NumPy: 1.26.4

## Usage
1. Clone the repository:

    ```
    git clone https://github.com/your_username/global-thresholding-otsu.git
    ```

2. Navigate to the repository directory:

    ```
    cd global-thresholding-otsu
    ```

3. Run the script:

    ```
    python global_thresholding_otsu.py
    ```

4. Provide the path to the input image when prompted.
