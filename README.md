# ChemComm_10.1039-D4CC04415K
A place to store initial structure and parameter files for the simulations used in the carbohydrate hydration analysis paper published 2024 in Chemical Communications.


**Polarization ON vs OFF:** 
All input files are provided for the mutual polarization turned on, which is the intended default for the AMOEBA/Tinker simulations. For the simulations with polarization turned off the same input files were used but the tinker '.key' files were modified by removing the line 'polarization mutual' and replacing it with the line 'polarizeterm none' as shown by the example key file. 


**Parameters:** 
All poltype output parameter sets were combined with amoebabio18.prm which includes water parameters


**XYZ files:** 
The structure files provided are the dynamics input files, post minimization and centering, except for the specified no-preminimization alpha directories.
