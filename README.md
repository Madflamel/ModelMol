This is a personnal repository used for a program to handlle gaussian computations for molecular modelisation and share it with my class.
USE AT OWN RISK it is an amateur side project, there is no guarantee of its stability.
Functionality uncertain, as it is dependant on another scipt that is internal to our institution, but feel free to use what you can.

TO SETUP Doopid.py :
The program needs to be setup in a work file that contains :
- the program itself
- the gaussian script
- a "Logs.txt" file for storing bash commands return/error codes
- a "Geometries" directory for storing .xyz geometries generated using Avogadro (unsure for other programs)
- a "Results" directory for storing previous calculations and avoid them being overwitten by newer files of the same name. This directory is to contain an "Inputs" dir (for .com files), an "Outputs" dir (for .log files) and a "Checkpoints" dir (for .chk files).

Calculations results while be directly stored in the work directory, until a file of the same name takes their place and they are displaced to Results.
