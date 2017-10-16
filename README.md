# optimizer

This repository contains benchmark quantum circuits before and after
optimization.

The circuit optimizations were carried out using the techniques
detailed in the following paper.

* Y. Nam, N.J. Ross, Y. Su, A.M. Childs, and D. Maslov. Automated
  optimization of large quantum circuits wih continuous
  parameters. October 2017.

The circuits are

1. Circuits for the Quantum Fourier Transform.

2. Adder circuits based in the Quipper library.

3. Adder circuits based on the Quantum Fourier Transform.

4. Product formula algorithms for quantum simulation.

5. A variety of circuits that optimized in prior approaches. Which
include arithmetic circuits, multiply controlled-toffoli gates, and
Galois Field multiplier circuits.

All circuits are are given in the ASCII format of the Quipper
language. See http://www.mathstat.dal.ca/~selinger/quipper/ for more
information.

Questions and comments can be addressed to: ynam@wesleyan.edu