## Finding Lane Lines on the Road
A software pipeline that uses traditional computer vision (CV) techniques to identify and track the position of lane lines in a video stream. 


## Pipeline

**Grayscale** 
[greyscale](greyscale.png)

**Gaussian Smoothing**

**Canny Edge Detection**

**Region of interest mask**

**Hough edge detection**

**Extrapolate Lane Line Position**

**Apply color and transparency to lines**





## Dependencies 
* Python 3
* Numpy
* matplotlib
* OpenCV
* Jupyter Notebook
* moviepy

Note: I recommend installing the Anaconda Python 3 distribution from Continuum Analytics <A HREF="https://www.continuum.io/downloads" target="_blank">here</A> because it comes prepackaged with many of the Python dependencies. Also note that Udacity has a nice Anaconda environment that includes many of the dependencies used in the Self-Driving Car Nanodegree: [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md)

## Running the code 
The project is completed in a Jupyter notebook. 
You will complete this project in a Jupyter notebook. To start Jupyter in your browser, run the following command at the terminal prompt and within your Python 3 environment:

`> jupyter notebook`

A browser window will appear showing the contents of the current directory.  Click on the file called "P1.ipynb".  Another browser window will appear displaying the notebook. 
