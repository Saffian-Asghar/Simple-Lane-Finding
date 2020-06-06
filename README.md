# Finding Lanes

<p align="center">
    <img src="https://github.com/Saffian-Asghar/Simple-Lane-Finding/blob/master/img/combo_image.jpg?raw=true" width="640" alt="combo_image" /><br>    
</p> 

## Intro
This project aims at finding lanes on a road from a video using OpenCV-python and NumPy. This is an assignment project from the "The Complete Self-Driving Car Course" by Udemy.
## Requirements
* python3
* opencv-python
* matplotlib
* numpy
## Methodology
* Get raw image from an RGB camera
<p align="left">
    <img src="https://github.com/Saffian-Asghar/Simple-Lane-Finding/blob/master/img/test_image.jpg?raw=true" width="520" alt="test_image" /><br>    
</p> 

* Apply Canny Edge Detection (OpenCV)
<p align="left">
    <img src="https://github.com/Saffian-Asghar/Simple-Lane-Finding/blob/master/img/canny.jpg?raw=true" width="520" alt="canny" /><br>    
</p> 

* Get the required region of interest to work on
<p align="left">
    <img src="https://github.com/Saffian-Asghar/Simple-Lane-Finding/blob/master/img/cropped_canny.jpg?raw=true" width="520" alt="cropped" /><br>    
</p> 

* Compute Hough Transform of the image we got in previous step
* Make an empty image with lines drawn using the image in previous step
<p align="left">
    <img src="https://github.com/Saffian-Asghar/Simple-Lane-Finding/blob/master/img/line_image.jpg?raw=true" width="520" alt="lines" /><br>    
</p> 

* Combine the two images using addWeighted from OpenCV
<p align="left">
    <img src="https://github.com/Saffian-Asghar/Simple-Lane-Finding/blob/master/img/combo_image.jpg?raw=true" width="520" alt="lines" /><br>    
</p> 
