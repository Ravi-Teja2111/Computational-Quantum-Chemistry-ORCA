This directory contains the computational chemistry files for Chlorobenzene using the ORCA software package. 
This study focuses on the electronic structure and geometry optimization of a monosubstituted benzene ring.

File Name,Description
chlorobenzene.inp,            "Input File: Defines the level of theory (e.g., B3LYP or PBE0), basis set (e.g., def2-SVP), and the Cartesian coordinates for C6​H5​Cl."
chlorobenzene.out,            "Output File: The primary log containing the SCF convergence, final electronic energy, and molecular orbital analysis."
chlorobenzene.property.txt,   "Properties: Detailed data on the dipole moment, Mulliken populations, and electrostatic potential."
chlorobenzene.bibtex,Citations: Generated references for the specific functionals and algorithms used in this run.

File Execution
orca chlorobenzene.inp > chlorobenzene.out
