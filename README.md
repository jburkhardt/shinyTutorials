# Shiny Tutorials for Statistics Instructors

This repository contains the source code for a [MOSAIC Project](http://mosaic-web.org/) tutorial.  It is intended for statistics instructors who would like to write their own [Shiny](http://shiny.rstudio.com/) apps for classroom use.

## Overview

Shiny makes it easy for R users to develop responsive, R-powered web applications.  As you probably know, either from your own initial forays into Shiny or from the <a href = "http://shiny.rstudio.com/tutorial/" target = "_blank">Shiny Tutorial</a>, creating simple apps is no problem, and probably you have some ideas for teaching apps that could be written using just the tools developed in the Tutorial.

But some teaching apps appear to be quite complex.  Consider, for example, <a href = "http://homer.shinyapps.io/SlowGoodness" target = "_blank">this app</a> which aims to introduce the student to the Chi-Square Test for Goodness of Fit.  The app takes the user through a simulation process, keeping track of the results of simulations as they accumulate, permitting the viewer to consider the results from several points of view, and allowing the viewer to start over, perhaps with new data.

The aim of this tutorial is to take you step-by-step through the construction of a reasonably full-featured simulation app that lets students explore, through simulation, the coverage properties of the classical t-intervals for a population mean.  After completing the tutorial you will be able to write your own simulation apps---hopefully having been spared some of the struggle that I went through when I first learned Shiny in the Spring of 2014.

## Prerequisites

This tutorial assumes that you have:

* **familiarity with R**.  We'll assume some basic facility in R programming and that you can at least read and understand R code that creates custom plots in R's base graphics system.  For the most part our explanation of R code will be limited to its relationship to app-building.
* **an introductory knowledge of Shiny**.  All necessary prerequisites inthis area can be acquired by watching Garret Grolemund's excellent three-part webinar on *How to Start with Shiny*.  (See R Studio's <a href = "http://www.rstudio.com/resources/webinars/" target = "_blank">webinars</a> page.)

## How to View the Tutorial

### Git Users

You may view the tutorial on your own machine:

* Clone this repo into your computer.
* In the cloned repo, open the directory `sim_tutorial_Rmd` and find the file `tutorial_sim.Rmd`.
* Open the file and run it.  (It runs as a local shiny app.)
* Enjoy!

### Non-Git Users

If you don't use Git, then you may view the tutorial at the following URL:

>[http://homer.shinyapps.io/sim_tutorial_Rmd](http://homer.shinyapps.io/sim_tutorial_Rmd)

**Request**:  The above URL is my `shinyapps` site, for which I get a limited number of user-hours per month.  If you are a GitHub user, then please do not view the tutorial at the above URL.   Instead, view it locally by following the directions for Git users.