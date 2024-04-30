# CardiacMRIModel
Implementation of a machine learning pipeline to model downsampling in cardiac MRI from the Sunnybrook cardiac MRI database

## **A machine learning approach to reduce cardiac MRI acquisition time**
The script below was written by Jacob Scherba.

### Overall Approach
Using data from the Sunnybrook Cardiac Database, I trained a convolutional neural network to classify cardiac MRI data into one of 4 diagnostic categories. By modeling the physical layer of MRI acquisition as a 2D mask in k-space, I was able to identify a possible pattern of important image information. Using the assumption that this information could be retained while removing some iterations of MRI acquisition, I was able to reduce the modeled MRI acquisition time by 30% without significantly impacting diagnostic accuracy. These data support the investigation of streamlined cardiac MRI acquisition to promote patient comfort and improved utilization of hospital resources.
