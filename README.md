# Finger-detection-and-counting
This is a computer vision project that detects the finger and count the number of fingers raised.

Here we have used the thresholding technique to grab the foreground of the image and get the External counter.
To count the no of fingers we have used Convex hull algorithm.

First we calculate the running average of the background values of certain region of interest using function calc_accum_avg() so that we can keep a track of change in the ROI.

Then we segment the hand region in the frame by finding the external counter of the image.
After getting the hand we count the no of finger being held up.

