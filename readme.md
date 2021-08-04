# Testing the Fidelity of the Quantum Teleportation Protocol on an IBM Quantum Computer
This is a repository for my final writeup for Physics 707 - Quantum Computing Lab, at University of
Wisconsin-Madison as part of the MS Physics Quantum Computing Program (2020-2021).

## Problem Statement
Use the Qiskit SDK to simulate the famous quantum teleportation protocol.  Then modify it to run on the 
open source IBM hardware, which has the peculiarity that it cannot run further gates after measurements are 
made.  You will therefore need to take advantage of the deferred measurement principle.  Run the protocol on 
a variety of input states, and quantitatively evaluate the results. Write a paper to explain the teleportation 
protocol,  why it cannot be run directly on the IBM hardware, how to use the deferred measurement principle, 
and your analysis of the results.