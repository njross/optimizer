# optimizer

This repository contains benchmark quantum circuits before and after
optimization.

The circuit optimizations were carried out using the techniques
detailed in the following paper.

* Y. Nam, N.J. Ross, Y. Su, A.M. Childs, and D. Maslov. Automated
  optimization of large quantum circuits with continuous
  parameters. October 2017.

The circuits fall into three categories.

1. Components of Shor's factoring oracle: Quantum Fourier Transform
(QFT) circuits, adder circuits from the Quipper arithmetic library,
and QFT-based adders. These circuits can be found in the
QFT_and_Adders folder.

2. Circuits for quantum simulation using product formulas. These
circuits can be found in the PF folder.

3. Arithmetic and Toffoli circuits. These circuits can be found in the
Arithmetic_and_Toffoli folder.

All circuits are are given in the ASCII format of the Quipper
language. See http://www.mathstat.dal.ca/~selinger/quipper/ for more
information.

Questions and comments can be addressed to: ynam@wesleyan.edu