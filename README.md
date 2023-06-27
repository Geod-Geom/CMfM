# CMfM

Crack Monitoring from Motion (CMfM) integrates photogrammetric techniques with deep learning methods for the automatic detection and monitoring of cracks. CMfM uses a series of images collected by moving cameras to monitor crack propagation over time. Unlike conventional techniques, CMfM does not require fixed artificial targets and overcomes the limitations of using a fixed camera of the 2D DIC. 

CMfM employs a Convolutional Neural Network (CNN) for automatically detecting the shape of the cracks and a skeletonization approach for delineating the center line of the defects and automatically selecting the points of interest around the cracked area. Then, we compute the change in the distance between the automatically selected points on the left and right sides of the crack for estimating the crack width propagation over time. The proposed approach is based on homography estimation and template matching techniques.
