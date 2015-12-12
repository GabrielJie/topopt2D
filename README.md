# topopt2D
##Topology optimization using images to control load, support and passive elements

Adaptation of python code taken from http://www.topopt.dtu.dk.
Loads and supports can now easily be drawn in any image processing software. The number of elements is not hardcoded but taken from the size of the images.

![load direction](https://github.com/worbit/topopt2D/blob/master/map.png)

A vertical load (down in y-direction) is an orange pixel, a load from left to right is greenish etc.
For y-support, the red channel must be 255, for x-support the green channel must be 255. For both x and y, the pixel must therefore be yellow.
