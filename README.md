fractals-are-fun
================

Fractals: They continue to be fun. A few simple fractal pattern programs


# Escape Time Fractals in Julia #

Prerequisites: Julia v0.2, Cairo.jl, Tk.jl

Load fractals.jl and functionDiver.jl in the REPL and open a viewing window with

    Diver.view(fractal; [domain=(x=-2:1, y=-1:1), w=800, h=600, color_map=RedBlue])

Available fractals are:

    Fractals.burning_ship
    Fractals.mandelbrot
    
Drag and click to zoom in on a region of interest, right click to zoom back out
