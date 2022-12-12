# Handwritten-Digit-Recognition
A Machine Learning Project in Python that provides a GUI window with a canvas to enable user to draw digits and has a trained CNN Model to predict the digit.
About the Project: 
Harnessing the power of machine learning, this project aims at building a software which can read and analyse human writing. Users are provided with a GUI interface, where they can draw digits on the canvas, as inputs for the model to recognise.
With apt resources and guidance, we can work similar strategies to train more sophisticated models, powering software solutions in different spheres of life, from aiding elementary learning, to helping organizations with document digitalization.

***A brief description*** 

**Modules Used:**

*Tensorflow* : An open source software framework to build and train machine learning models. This project focuses on building and training deep neural networks. Tensorflow contains the MNIST dataset which is a large database containing handwritten digit images(0-9) that are used for training and testing the model.

*NumPy* : A python library that supports multi-dimensional arrays and matrices and contains variety of functions to operate on these.
Operations include reshaping large arrays before convolutional operations. 

*CV2* : Used to load image from specified file that are transformed into arrays. The images can be operated on as arrays to change from color to black-white, to grey, to RGB or to resize image, etc.

*Matplotlib* : A python library used for creating 2D graphs and plots. Module pyplot helps to plot images or graphs.  
Tkinter : A standard python interface to utilize TK GUI toolkit. TK library has all functions needed to build a GUI interface for the Python software.

*Pygetwindow* : A python module to extract the user input by locating GUI window.

*Pyautogui* : A python module to get screenshot of the user input that can be converted into a .png input for the application.

*Pillow(Image, Imagegrab)*: Python Imaging Library is a python module which provides the python interpreter with image editing capabilities. The module also provides a number of factory functions, including functions to load images from files, and to create new images.

**Files Used:**

*Model.py* : This file contains the python code to build and train the Deep Learning Model and to convert the trained model into a Jason file for easy transfer.

*Application.py* : This file loads the trained model from Jason file and the weights. This file also contain the source code for the interactive GUI window that contains all the visible user-defined functions.

*Trained_Model_010921.jason* : Jason file storing the trained model.

**Menu Options:**

Save:				Save the input drawing

Clear: 			Clear the canvas

Test: 			Test the input

Try Again: 	Reset the window

Quit: 			Quit application
