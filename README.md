# Software Carpentry - Final Project

### Author
Yupin Shi

## Background Information
The project is used to assist my research on finite element modeling. I am using a finite element analysis software ABAQUS and a user-defined element subroutine to run simulations on bilayer soft robots. To run the simulations, I need to do the following:
* Generate the geometry, node coordinates, element nodes and node/elemnts sets for boundary conditions in ABAQUS
* Generate an input file (.txt) that includes the geometry information
* Add other information (material properties, boundary conditions, initial conditions, and subroutine related information, etc) in the input txt. File
* Draw a diagram for the boundary conditions
* Run the input file and subroutine in command line

To run the model with different geometry, I need to redraw the geometry in ABAQUS and redefine the node sets and element sets. In order to save time, I wrote this python code that automatically generate the input file that contains the geometry information without using the user interface. 

## What does the code do
* Generate in a txt file that includes the following geometry information:
  * node coordinates
  * element nodes
  * node/elemnts sets for boundary conditions
* Generate an image that illustrate the boundary conditions
* Generate an excel file that lists the important parameters
