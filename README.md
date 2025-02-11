# airfoil_simulation
tool for quickly predicting airfoil perfomance

This repo aims to create

a. A function to generate and plot points along the camber line based on user defined
functions [y = f(x)], including the one for NACA airfoils.
(Consider normalized airfoil with leading edge at x = 0 and trailing edge at x = 1.)
b. A function to compute the slope of the camber line at any given point along the
chord length.
c. A function to compute Cl of the thin airfoil at a given α based on thin airfoil theory.
d. A function to plot vector field around the airfoil based on circulation distribution,
and compute circulation due to airfoil through line integral.
e. A main function that takes user inputs and combines functionality of all the above
functions
