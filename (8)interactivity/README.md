# Homework Week 8 - Interactivity

## The Concept
For this weeks assignment, I wanted to use D3 to filter out individual data points based on user interaction, in this case click events. I also wanted to ensure that, if the range of the data changed due to this interaction, the colour scale would also change. I intended to extend this to using geographic data, but time did not permit.

## The Data
For the purposes of experimentation, the data values were hard coded into the code. An extension to this project would want some form of geographic heatmap data, even something as simple as population size.

## The Viz
The viz is laid out in a 3x3 grid in order to demonstrate the proof of concept. Each rectangle contains a data value from 1-9, read left to right, top to bottom. Each value is represented by a colour value ranging from "yellow" to "red". Every rectangle is clickable, allowing the user to either include or exclude it in the data set. If this action would cause the scale to change (e.g by remove the min or max data value), the colour scheme is recomputed with the new scale

## Links

The source code is available [here](https://github.com/tkcram/pivf22/tree/main/(8)interactivity) and the output image is available below

![The viz pre-interaction](https://raw.githubusercontent.com/tkcram/pivf22/main/(8)interactivity/interactivity_before.png) "Before Interaction") 

![The viz post-interaction](https://raw.githubusercontent.com/tkcram/pivf22/main/(8)interactivity/interactivity_after.png) "After Interaction") 
