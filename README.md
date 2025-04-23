# Face Detection Project

This project implements a simple face detection system using OpenCV and Python. It can detect faces in images and draw rectangles around them.

## Requirements

-   **opencv-python**:  OpenCV library for Python. You can install it using pip:
    
    ```bash
    pip install opencv-python
    ```
    

## Files

-   `Face_Detection.ipynb`:  Jupyter Notebook containing the Python code for face detection.
-   `haarcascade_frontalface_default.xml`:  Haar cascade classifier XML file for frontal face detection.
-   `download.jpg`: An example image file.

## How to Use

1.  **Install Dependencies:**
    
    ```bash
    pip install opencv-python
    ```
    
2.  **Place Files:**
    
    -   Ensure all files (`Face_Detection.ipynb`, `haarcascade_frontalface_default.xml`, and `download.jpg`) are in the same directory.
    
3.  **Run the Notebook:**
    
    -   Open and run the `Face_Detection.ipynb` notebook. The notebook will:
        -   Load the Haar cascade classifier.
        -   Load the image (`download.jpg`).
        -   Detect faces in the image.
        -   Draw rectangles around the detected faces.
        -   Display the image.
        -   Save the modified image.
