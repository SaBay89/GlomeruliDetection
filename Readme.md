# Glomeruli Detection with YOLOv4

## Description of the Project

A easy use and already trained Network to detect healthy Glomeruli in
HE, Jones and PAS stainings of kidney sections. 
An Execution of the Detector on example images is included "  ".
It is possbile to combine this detector with any camera such as MicroscopcCamera.

## Further goal of this Project

Actually the Detector is limitied on healthy Glomeruli.
It is an initial project.
in the future i will extend the detector to discriminate
between healthy and skelorized Glomeruli.
Further plans are combine the detector with the network U-net for segmentation for perfect croping of detected Glomeruli.

# Motivation

During my ph.D i worked in the Nephorlogy and anaylzed a lot of stainings, the task was to count, classife and measure the size
of the Glomeruli. I did it manually and it was very boring.
But with the new A.i technolgies we can automate this boring task. This is why i will share my experencies with other interested colleques.


## Prequisities to use :

- Several Packages (Jupyternotebook,Python, Numpy, CV2 ..) is needed.
  The easiest way is to download and install the Distribution: [Anaconda] (https://www.anaconda.com/products/individual)
   

- After that, install [open-cv] (https://pypi.org/project/opencv-python/) via pip or command line 

- After cloning, please download the [weights](https://drive.google.com/file/d/1uC0ijQRoxmO-SvAK0o0HJ8q1JzCpPVbj/view?usp=sharing)
  into the folder weights !

If there any conflicts or questions please contact me.
  


![Example for HE staining!](Example.png "InputImages and Detection")
