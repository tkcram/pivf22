# Homework Week 3 - Barchart & CSV

For this week's homework, I created a barchart showing the the most frequently occuring colours used for pieces in LEGO sets in 2021, a mouthful for which the title is still being workshopped. The chart is built up based on the template we used in class, using data provided by [Rebrickable](https://rebrickable.com/downloads/). A snapshot of the data was taken approximately a year ago for another project, and cajouled into giving three columns - Colour, a hex code representation of said colour, and total number of pieces for that colour. This was exported as a CSV, and loaded directly into the D3 code. From there, the following modifications were made to the template: 

1) The bars were given a fill using the hex code in the data, and a stroke to ensure colours such as 'white' were legible. 
2) The vertical axis was formatted to give the short form of the numbers (80k vs 80,000)
3) Some minor style adjustments were made, such as removing the outermost tick mark.

[link to source code](https://github.com/tkcram/pivf22/tree/main/(3)barchart)

![a simple scatter plot](https://raw.githubusercontent.com/tkcram/pivf22/main/(3)barchart/barchart.png) 

