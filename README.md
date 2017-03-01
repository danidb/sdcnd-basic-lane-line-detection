## Basic lane detection with OpenCV

The work related to this project is entirely contained in the jupyter notebook `basic_lane_detection.ipynb`.

## Overview

### Objectives
This project explores common approaches to edge detection applied in an automotive setting. The Canny algorithm, and the Hough Transform are applied to detect candidate lane lines in a predefined region of interest.

To model the lane lines, a linear model is fit to the right lane, and another to the left lane. In video, exponential smoothing is applied to the paramters of the mode.

### Development System
This work was developed and tested with Python 3.5.2, and Anaconda 4.2.0 (64-bit) on a MacbookPro 11'3 running Debian 8 Jessie.
