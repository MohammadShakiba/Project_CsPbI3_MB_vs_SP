## Molecular dynamics calculations

`cp2k_md_input_file.inp` - this file contains the input for a md calculation with CP2K. Actually, this file contains the restart file after the thermalization of the MD. Use this file for directly producing a production MD trajectory.

This folder contains the files `BASIS_MOLOPT`, `POTENTIAL`, and `dftd3.dat`, whcih contain the Gaussian basis sets, pseudopotentials, and dispersion corrections, respectfully.

The submit file contains bash commands needed to run the CP2K input file on the UB CCR.
