This repository contains the code developed to study the CYGNO experiment sensitivity using the BAT library

## Prerequisites
You need to have ROOT installed to be able to install BAT. Follow the instructions here to install BAT: https://github.com/bat/bat  

## Setup
Once BAT is installed, you need to set the number of events in the input files:
- background events: input/background.txt
- data events: input/data.txt

## Compilation
Compile the code to generate the executable:

```
make
```

## Running the code
After compilation, run the code using:

```
./runfit
```
The output will be a ROOT file containing mub and mus  

Note: You may need to create the results folder (the folder where the output is saved) before running the code.
