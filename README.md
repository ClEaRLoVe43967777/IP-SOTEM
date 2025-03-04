# One-Dimensional Forward Modeling of Electrical Source TEM Based on the Cole-Cole Model

## Project Description
This project implements one-dimensional forward modeling of Time-Domain Electromagnetics (TEM) based on the Cole-Cole model. This model is widely used in geophysical exploration to analyze the electrical characteristics of underground materials.
## File Structure
"IP-SOTEM.f90": Main program file that executes the forward modeling, contains the implementation of the Cole-Cole model.
## Installation Instructions
Please ensure that you have a Fortran compiler installed, such as GNU Fortran (gfortran).

### Compile and Run
1. Clone the repository to your local machine:
2. Compile and run the Fortran file.
3. 
### Usage
Enter the filename of the forward modeling file (in DAT format), and the program will automatically perform the simulation and write the results to a DAT file.

### Quick-test file
MH1.DAT is the forward modeling file we uploaded. After running the Fortran code, simply input this file name to perform the forward simulation.
