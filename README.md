# cggc_rg
A maintained and enhanced version of the CGGC-RG algorithm family.

## Background
This repository is based on the C++ source code of the Randomized Greedy (RG) algorithm for graph clustering and its derivates
which apply the Core Group Graph Clustering (CGGC(i)) schema.

The original code can be found here http://www.umiacs.umd.edu/~mov/ and the copyright is held by *Michael Ovelgönne* and the *Karlsruhe Institute of Technology* (of which the creator of this repository is a part of).

### Original copyright disclaimer
>Copyright 2009-2012 Michael Ovelgönne and Karlsruhe Institute of Technology
>
>This is experimental code. Please use it with caution.
>The software is provided "as is" and is free for academic and non-profit use. 
>This software or any part of it must not be distributed without
>prior written agreement of the copyright holders.

### Purpose
The purpose for this repository is to maintain a version of the source code which 
- does not throw errors/warnings using current compilers and library versions
- is correctly implemented in terms of the published description of the algorithm
- can be used by the Python binding [pycggcrg](https://github.com/KIT-IISM-EM/pycggcrg) which allows calling the different algorithms directly from Python

## References
> Ovelgönne, Michael, and Andreas Geyer-Schulz. 2013. “An Ensemble Learning Strategy for Graph Clustering.” In Graph Partitioning and Graph Clustering, edited by David A. Bader, Henning Meyerhenke, Peter Sanders, and Dorothea Wagner, 588:187 – 205. Contemporary Mathematics. Providence: American Mathematical Society.

