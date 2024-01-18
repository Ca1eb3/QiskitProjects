# QiskitProjects
This repository contains small Qiskit projects/algorithms that I am using to track my progress in learning to code with Qiskit. 
Below is a list of the different projects that you can find in this repository with a brief description of each.

## IBM Quantum Learning
+ All files in this folder follow various tutorials/lessons from IBM Quantum Learning modules

## Thue Morse Generator
+ The Thue Morse sequence is a sequence defined by T:0 = 0 and each subsequent T:n = T:n-1 concatenate the complement of T:n-1
+ The algorithm I developed uses the column vector representation of a classical state and the pauli x operator to generate the next term in the Thue Morse sequence
+ While not a true quantum algorithm this project helped me become more comfortable setting up Quantum Circuits and applying operations to statevectors using Qiskit

## Deutsche-Jozsa Algorithm
+ Given an arbitrary function f:{0,1}-->{0,1} Deutsche's algorithm determines whether the function is constant or balanced
+ Deutsche-Jozsa algorithm generalizes Deutsches algorithm to a function f:{0,1}^n-->{0,1}.
+ This is my first attempt at implementing a true quantum algorithm using Qiskit

