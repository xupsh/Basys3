# Digital Design Github
This repository provides Digital Design Libraries and Projects for Vivado IP Integrator 

The board features an Artix series 7 Xilinx FPGA and is an ideal platform for low cost teaching and student projects.
For questions, please contact the [Xilinx University Program](mailto:xup@xilinx.com).

### How to use these files

### XUP_LIB and 74LSXX
There are two digital libraries for Vivado IP Integrator that include basic logic blocks for schematic entry and teaching basic logic design; XUP_LIB (AND, OR, NOT, XOR etc) and 74LSXX models. 
These libraries include IP blocks are intended for classroom teaching and can be used with the Vivado IP integrator graphical environment to design, simulate and build designs for Xilinx FPGAs using schematics.

## To use the libraries
Create a new Vivado project, and in the *Project settings* (In Vivado, Tools > Project Settings), select the IP tab, and in the *Repository Manager* tab, add the directory of the XUP_LIB and/or 74LSXX folders. You will then be able to add these IP blocks to your designs in IP integrator. 

## To use a project
e.g. Ripple Carry Adder: ./Projects/Logic_Design/CN_Design/Ripple_Carry_Adder
See the readme.md file in the root directory of the project.

The project can be built by opening Vivado, and running the script provided for each project. 

You can open the script, which is commented, to understand how the project is built
