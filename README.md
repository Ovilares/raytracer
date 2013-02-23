Raytracer
=========

This is a simplest possible raytracer written in C, with minimal usage of
pointers and external libraries, for easy understanding of the basic theory ([more details](http://shiben.blogspot.in/2012/11/simple-and-easy-ray-tracer.html)).

We did not make a makefile because it's too easy to compile:
`gcc raytracer.c -lm` 

Run the default executable created by gcc named as a.out as:
`./a.out`

Above executable will create a ppm file, to view, use ImageMagick as:
`display output.ppm`


Some points for performance sake:
* Image Size: for quick testing, use something like 320x240
* Recursion Depth: Can be kept 0 for no reflections/refractions
* Cone and Cylinder can use smaller resolution, default image uses 32
* Sphere resolution, unlike Cone and Cylinder, is power of 4

Thank you for downloading our code. 

Output Image
------------
![Raytraced Image](https://raw.github.com/bnaveenkr/raytracer/master/output.png)

Authors:
--------
* Shiben Bhattacharjee
* Naveen Kumar Bolla

Special mention of our dear friend:
-----------------------------------
* Yash Agrawal
