FF-PETSc Examples
===

This is a repository discussing various examples of the PETSc module
in FreeFem. PETSc is short for *Portable Extension Toolkit for
Scientific Computing* and FreeFem is an open--source high level
programming language for implementing finite element method similar to
FEniCS, deal.ii etc. FreeFem has support for PETSc libraries that
could be used to solve large systems. A full--fledged tutorial can be
found here - made available by the FreeFem folks. This is an attempt
to make the existing tutorials a little more details, attaching some
of my own comments along with the code.

**Disclaimer: I did not create these tutorials in the first place and
is merely an extension of what the FreeFem developers have done. Please refer to the original tutorial [here](https://doc.freefem.org/documentation/petsc/index.html).**

I will keep updating the details of the various example scripts below:

1. `example1.edp`: A simple describing the difference between PETSc
   Numbering and the global numbering. The example also contains routine
   to perform the distribution of the meshes among the various processes.
