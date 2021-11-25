# Bankers Algorithm
Bankers Algorithm Homework

## About The Project
This code takes in an input text file to read the number of processes and a matrix to determine what is the safe sequence for running these processes to avoid deadlock.


### Installation
To install the code for this project, either copy and paste the code into a file on your computer, or type the following command. This was installed on Ubuntu 21.1

`apt-get install gcc-g++`

## Usage
To use/compile this program, run the following commands.

`g++ bankers.cpp -o bankers`

`./bankers`

The program takes in 5 processes, therefore: `const int processes = 5;`. And it reads 3 processes, therefore: `const int resources = 3;`.

If you want it to run different numbers for how much is allocated, the max, and available resources, go into the input file and change the appropriate numbers.

## Example of Output
The following is the safe sequence for the processes to run:
 P1 -> P3 -> P4 -> P0 -> P2


