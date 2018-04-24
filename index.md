# About

### [Resume](schoonover_cv.pdf)


# Software Projects
## [SELF-Fluids](https://schoonovernumerics.github.io/SELF-Fluids/)
 Spectral Element Libraries in Fortran for Fluids
 
 SELF is a set of modules that define Fortran data structures and type-bound procedures that can be used for developing spectral element solvers for conservation laws. The highest level API of SELF allows one to compute spectrally accurate differential operators (divergence, gradient, and curl) on an unstructured isoparametric mesh. Each routine has a CUDA accelerated counterpart. Some tools are provided for handling these computations with domain decompositions, so that scientific software developers can leverage MPI and MPI+CUDA accelerations.
 
 SELF-Fluids is a particular encantation of the SELF for solving the Compressible Navier-Stokes equations. Currently, these equations of fluid motion are discretized using the Nodal Discontinuous Galerkin Spectral Element Method with Legendre Gauss quadrature. SELF-Fluids employs a Lax-Friedrich's approximate Riemman Solver to estimate momentum, mass, and energy fluxes between neighboring elements. The primary time integrator is Williamson's Low Storage 3rd Order Runge Kutta. Implicit and semi-implicit time integrators are currently in development. For more information on this project, see the [SELF-Fluids github io page](https://schoonovernumerics.github.io/SELF-Fluids/).
 
 
 ## [GeoBarS](https://schoonovernumerics.github.io/GeoBarS/)
 
 ## [FEOTS](https://github.com/lanl/FEOTS) 

