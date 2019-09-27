# fldmaker
A Fortran program designed to write .fld files, which are then used to visualize particle simulations.

Created out of a necessity to omit the repetitive process of editing an automatically generated fld file.
Features a simple interface in the cygwin command prompt which asks the user for the total time and time interval in [seconds].

Program is to be compiled in a cygwin terminal with the following command:
          "g95 ./DEMFB-fld.f -freal-loops"
          
