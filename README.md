# Problem Statement
Printed circuit board (PCB) is the fundamental carrier in electronic devices on which a great number of elements are placed and the quality of the PCB will directly impact the performance of electronic devices.
To avoid shortcomings of manual detection, an automated optical inspection (AOI) based on machine vision need to be proposed.

**Major Use Case** - Detection and Classification of defects in PCBs

# Process at a Glance
![Product_flow_1](https://user-images.githubusercontent.com/67309253/85369942-9da17400-b54b-11ea-8578-6bc97086061a.PNG)

# Requirements
* Python 3.6.5
* Python Packages
    * Cv2        : Open Source Computer Vision Library
    * Pandas     : for dataframe
    * Numpy      : for numerical computations
    * Flask      : web application framework
    * Os         : for interacting with the operating system
    * Tensorflow : Open Source Dataflow library
    * Keras      : Open Source Neural Network library
    * Glob       : for reading/writing files to specific directories
    * Shutil     : for high-level operations of files
    * Sklearn    : Open Source Machine Learning library
    
# Python Scripts
**Jupyter Notebook** - Final Product.ipynb  

# Dataset
* There are 693 images in total of 10 different templates of PCBs 
* Types of defects :
    1. Missing Hole
    2. Mouse Bite
    3. Open Circuit
    4. Short Circuit
    5. Spur
    6. Spurious copper
* **For Classification** - A total of 3200 defects (80%-Training & 20%-Testing)
    * Training data - 2560 defects
    * Testing data - 640 defects 
    
# Code Description
1. Reading the input images from the dataset directory and storing in data and template lists
2. ### Image Processing Algorithms ###
   * Converting the images to grayscale and applying a Median Filter for denoising.
           
   * 

    
    
    
