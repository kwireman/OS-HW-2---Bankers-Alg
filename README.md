# Bankers Algorithm
Bankers Algorithm Problem

## About The Project
The code for this project covers the bankers algorithm problem. In this problem there are a specific number of processes given and a certain number of resources. Each process has a specific amount of each resource already allocated, and needs more to complete its instructions. This code finds a path for these processes to run so that deadlock is avoided. This project implements a solution to this problem using an input file and a main file.

`apt-get install gcc-g++`

### Installation
To install the code for this project, either copy and paste the code into a file on your computer, or type the following command.

## Usage
To use and compile this program, run the following commands.

`g++ bankers.cpp -o bankers`

`./bankers`

To change the number of processes or resources used, go into the code and change the 5 in `const int processes = 5;` or the 3 in `const int resources = 3;` to whatever amount you would like.

If you want it to run different numbers for how much is allocated, the max, and available resources, go into the input file and change the appropriate numbers.

## Example of Output
The following is an example of an output when the input is the same as in the given input file.

