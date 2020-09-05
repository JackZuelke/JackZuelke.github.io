---
layout: project
type: project
image: images/graph_visual.jpg
title: Polynomial Derivative Calculator
permalink: projects/calculator
# All dates must be YYYY-MM-DD format!
date: 2018-12-20
labels:
  - Java
  - EZ.java
  - Calculus
summary: A polynomial derivative and antiderivative calculator I made as a personal project.
---

During Christmas break I wanted to put my knowledge to the test, so over the course of 1-2 days I made a derivative calculator, mixing skills I learned from both ICS 111 and Calculus I. The end result is a program which can read a user inputted polynomial function, and perform multiple actions on that function. Firstly, as long as there aren't any unknown constants as a result of integration, you can enter any x-value and get the y value of the function. Then you can input as many antiderivatives and derivatives as you'd like, minus the caveat that only C-G constants will be displayed, however the non constant terms will still be integrated; also due to the program doing calculations on functions in real-time, constants are lost during derivation.

Here is an example function, x squared, which has its points calculated to be added to a graph, as well as it's derivative 2x.

<img class="ui image" src="{{ site.baseurl }}/images/xsquared_example.jpg">

Example of antiderivations, and derivations back to the original function.

<img class="ui image" src="{{ site.baseurl }}/images/antiderivative.jpg">

As a last addition, I decided to have a simple graph displaying a visualization of the functions. The x and y axes are displayed along with inputs [-10, 10]. The image below shows the result of x squared, and it's derivative 2x. The graph can also be visually scaled to support higher y values. The graph made use of the EZ.java library.

<img class="ui image" src="{{ site.baseurl }}/images/graph_visual.jpg">



