# EX:04
# Image-transformations-OpenCV

# AIM

To write a Python program using OpenCV to perform various geometric transformations on an image such as translation, scaling, shearing, reflection, and rotation.

# SOFTWARE REQUIRED

Python 3.7 (Anaconda)
Jupyter Notebook (for interactive development and execution)

# EXPLANATION

Geometric transformations are image processing techniques used to manipulate the spatial orientation of images. These operations include shifting, resizing, flipping, shearing, and rotating images. OpenCV provides efficient functions to perform these transformations for various computer vision and image processing applications.

# ALGORITHM

Step 1: Import the required libraries such as OpenCV, NumPy, and Matplotlib

Step 2: Read the input image in color mode

Step 3: Perform image translation by creating a translation matrix and shifting the image horizontally and vertically using cv2.warpAffine()

Step 4: Perform image scaling by resizing the image to smaller and larger dimensions using cv2.resize()

Step 5: Perform image shearing using transformation matrices for horizontal and vertical shearing and apply them using cv2.warpAffine()

Step 6: Perform image reflection using cv2.flip() for horizontal, vertical, and both-axis flipping

Step 7: Perform image rotation using cv2.getRotationMatrix2D() and apply the transformation using cv2.warpAffine()

# RESULT

Thus, various geometric transformations such as translation, scaling, shearing, reflection, and rotation were successfully performed using OpenCV.
