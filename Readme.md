# Glomeruli Detection with YOLOv4

## Description of the Project

A easy use and already trained Network to detect healthy Glomeruli in
HE, Jones and PAS stainings of kidney sections. 
An Execution of the Detector on example images is included "GlomeruliDetection_from_Image.ipynb".
Depend on you hardware, it is possible to use images from different sources (MicroscopicCamera) as input for the Detector.
The training process is not included.

## Limitation and further goal of this Project

Actually, the Detector is limitied on **healthy Glomeruli** and **not for entire slides** !
Check the results in the folder images and the quality of the detection.
The numbers in the description of the images represents the zoom-factor.

In the future i will extend the ability of the detector to discriminate
between healthy and skelorized Glomeruli.
Further plans are to combine the detector with the network U-net for segmentation.

## Motivation

During my ph.D. i in the Nephrology i anaylzed a lot of  kidney stainings. My task was to count, classifie and measure the size
of the Glomeruli. I did it manually and it was very boring.
But with the new A.i technologies today and acessibility,
we can automate such taskes. 
Therefore i will share my experiences and want collabaorate with other motivated colleques to extend the Detector.

## Prequisities to use :

- Several Packages (Jupyternotebook,Python, Numpy, CV2 ..) is needed.
  The easiest way is to download and install the Distribution: **[Anaconda](https://www.anaconda.com/products/individual)**

- After that, install **[open-cv](https://pypi.org/project/opencv-python/)** via pip or command line 

- After cloning this repository, please download the **[weights](https://drive.google.com/file/d/1uC0ijQRoxmO-SvAK0o0HJ8q1JzCpPVbj/view?usp=sharing)**
  into the folder weights !

If there any conflicts or questions please contact me <samet.bayraktar@outlook.de>.
  

![Example for HE staining!](Example.png "InputImages and Detection")


# Literatur

**[YOLO](https://arxiv.org/abs/1506.02640)**
**[YOLOv4](https://arxiv.org/abs/2004.10934)**