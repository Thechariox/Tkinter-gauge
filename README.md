# Tkinter-gauge
![gauge circle](https://user-images.githubusercontent.com/125829209/219974606-cc038824-7c7b-4ed7-985b-4b0e1d9fefb1.PNG)

This is a Python code that implements a gauge circle using the Tkinter GUI toolkit.
The gauge is drawn as an arc with a value pointer, and it is divided into a number of range lines with labels. 
The gauge can be updated with a new value by moving the needle.

The GaugeCircle class takes several parameters that define the gauge circle's appearance and behavior, including:

parent: the parent widget where the canvas will be created.
canvas_height, canvas_width: the dimensions of the canvas where the gauge will be drawn.
radius: the radius of the gauge circle.
angle: the amplitude of the gauge in degrees, from 0 to 360.
low_r, high_r: the low and high values of the gauge.
nb_main_scale, nb_secondary_scale: the number of range lines for the main and secondary scales.
start: the start position of the gauge in degrees.
title, title_position: the title and position of the title.
unit: the unit of the gauge.

The __init__ method initializes the gauge circle by creating the canvas and drawing the circle, needle, and labels.
The update_gauge_circle method updates the gauge with a new value by rotating the needle. 
If the new value is outside the low and high values of the gauge, it is clipped to the low or high value

explanation made by chatgpt because i'm lazy and bad at explainning.
