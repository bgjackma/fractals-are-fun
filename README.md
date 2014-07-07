fractals-are-fun
================

Fractals: They continue to be fun. A few simple fractal pattern programs


# Escape Time Fractals in Julia #

![The Burning Ship]
(https://raw.githubusercontent.com/bgjackma/fractals-are-fun/master/escape_time/burning_ship.png)

Prerequisites: Julia v0.2, Cairo.jl, Tk.jl

### To Install Julia: ###

    sudo apt-get install julia

or similar

### To Install Required Packages ###

    julia -e 'Pkg.add("Cairo"); Pkg.add("Tk")'

### Diving into Fractals ###

The Function Diver will evaluate and color a binary function of x and y over a domain, it doesn't have to be a fractal.

    Diver.view(function; [domain=(x=-2:1, y=-1:1), w=800, h=600, color_map=RedBlue])
    
See example.jl for the simplest example

Available fractals are:

    Fractals.burning_ship
    Fractals.mandelbrot
    
Drag and click to zoom in on a region of interest, right click to zoom back out.
You can zoom down to the limits of 64-bit float precision
