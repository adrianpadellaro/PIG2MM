# PIG2MM
Sage notebooks for computations in permutation invariant matrix models


Most files you will find in this repository are jupyter notebooks for Sage.
Installation instructions for Sage+jupyter can be found at https://doc.sagemath.org/html/en/installation/index.html

The notebook `PIG2MM-Expectation-Values.ipynb` takes as input a directed colored graph and computes the 
permutation invariant 2-matrix expectation value using methods described in the paper associated with this code.
The notebook `PIG2MM-Observables-Generator.ipynb` takes inspiration from the double coset to construct the distinct graphs (in a form appropriate for the implementation)
that can be used as input to `PIG2MM-Expectation-Values.ipynb`.
