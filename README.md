# R-Workshop Intro To R Syntax

Material for intro to R Syntax workshop

Using the Rproj file and Rstudio open the Rmd file for each module.
Once open, compile it with the button: "Run Document".
This will create a shiny app that is fully contained and interactive.
The code chunks in the tutorial are fully interactive R sessions that keep the state from previous runs using the package `learnr`.
This provides a workshop with zero time spent on setup and leaves the time and attention to focus on R syntax exclusively.

So far 6 iterations of these workshops have given feedback to render the current modular approach. Each section builds upon the previous ones. The first begins with basic operators, variables, and built-in functions. Then the modules tackle data types and data structures: unidimensional homogeneous vectors and heterogeneous lists, two-dimensional homogeneous matrices, multidimensional homogeneous arrays and ultimately the multidimensional heterogeneous data frame. The last module presents user functions and the basics of flow control and iteration for programming.

Throughout the modules, there is an emphasis on the features that make R useful for data analysis and visualization. Base R's syntax is fully and natively vectorized, meaning there is no need to import libraries to write vectorized expressions. The basic operators use a technique called recycling to process vectors and matrices of incomplete size. and there are simple and reusable patterns for subsetting and manipulating the basic data structures.
