## Advanced Lane Finding
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

![Image of Processed Lane](result.png)

This Udacity project uses computer vision to label the lanes in a driving video, calculate the curvature of the lane, and estimate the distance of the vehicle from the center of the lane. The rest of the project writeup can be accessed via [PDF](P1.pdf) or [Jupyter notebook.](P1.ipynb)

Steps
* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply the distortion correction to the raw image.  
* Use color transforms, gradients, etc., to create a thresholded binary image.
* Apply a perspective transform to rectify binary image ("birds-eye view"). 
* Detect lane pixels and fit to find lane boundary.
* Determine curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

---

## How to Run the Project

#### Clone the repo
```
git clone git@github.com:ckirksey3/lane-detection-with-opencv.git
cd lane-detection-with-opencv
```

#### Set up your environment
If you don't already have tools like Jupyter and OpenCV installed, follow the [Udacity instructions](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/doc/configure_via_anaconda.md) to configure an anaconda environment that will give you these tools.

#### Run the notebook
```
jupyter notebook
```

#### Walk through the steps
To see the code in practice, execute each cell in succession by pressing shift + enter.
You can also run the whole notebook in a single step by clicking on the menu Cell -> Run All.
