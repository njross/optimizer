# optimizer

This repository contains benchmark quantum circuits before and after
optimization.

The circuit optimizations were carried out using the techniques
detailed in the following paper.

* Y. Nam, N.J. Ross, Y. Su, A.M. Childs, and D. Maslov. Automated
  optimization of large quantum circuits with continuous
  parameters. October 2017. Available from
  https://arxiv.org/abs/1710.07345.

The circuits fall into three categories.

1. Components of Shor's factoring algorithm: Quantum Fourier Transform
(QFT) circuits, adder circuits from the Quipper arithmetic library,
and QFT-based adders. These circuits can be found in the
QFT_and_Adders folder.

2. Circuits for quantum simulation using product formulas. These
circuits can be found in the PF folder.

3. Arithmetic and Toffoli circuits. These circuits can be found in the
Arithmetic_and_Toffoli folder.

All circuits are given in the ASCII format of the Quipper
language. See http://www.mathstat.dal.ca/~selinger/quipper/ for more
information.

The circuits before optimization use Hadamard gates, single-qubit
z-rotations, as well as NOT, CNOT, and Toffoli gates. The Toffoli
gates are sometimes expressed as a doubly-controlled Z gate conjugated
by Hadamard gates. The circuits after optimization use only Hadamard
gates, single-qubit z-rotations, NOT gates and CNOT gates.

The pre-optimized circuits in the QFT_and_Adders folder were generated
using the implementations provided with the Quipper language. The
pre-optimized circuits in the Arithmetic_and_Toffoli folder were taken
from the T-par repository which can be accessed at
https://github.com/meamy/t-par.

Questions and comments can be addressed to: ynam@wesleyan.edu
