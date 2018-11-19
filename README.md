# Quantum-Simulations

Section 1: Numerical Integration of 1D Schrodinger equation:
    Description: This short project is for simple numerical integrations of the 1D time-independent Schrodinger equation. At present this scheme uses Numerov's algorithm, intialised by a WKB approximation of the boundary conditions of the wavefunction and works for simple 1D symmetric potentials. A root-finding method is used to determine the energy eigenvalues based on a function that compares the gradients of left and right calculated wavefunctions at the matching point.
    TODOS: (In rough order of priority with a difficulty estimate)
          1) Write energy matching function (Easy)
          2) Adapt function so it can deal with classically allowed regions at the boundary (Easy)
          3) Allow the use of quantum super-symmetry WKB at low energies (Medium)
          4) Adapt for the time-varying Schrodinger equation (Medium/Hard)

Section 2: Density Functional Theory:
    Description: The successor project to section 1. Writing my own DFT code to run simulations of complex quantum condensed matter systems.
    TODOS:
          1) Finish section 1 to a reasonable standard before starting
