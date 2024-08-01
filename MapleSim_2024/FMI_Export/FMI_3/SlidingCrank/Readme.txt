Description:
SlidingCrank (highly constrained model) with 2 Arrays of outputs

FMI Type:
CoSimulation and ModelExchange

Platform:
x86_64-windows, x86_64-linux, x86_64-darwin, aarch64-darwin

Compilers:
gcc on linux64 and darwin64
clang on win64

Validation Tools:
FMPy 0.3.19
fmusim b20ed8c (x86_64-linux)

Command to reproduce:
fmusim --interface-type cs --stop-time 10 --input-file SlidingCrank_in.csv --output-file SlidingCrankCS.csv SlidingCrank.fmu
fmusim --interface-type me --stop-time 10 --input-file SlidingCrank_in.csv --output-file SlidingCrankME.csv SlidingCrank.fmu

CONTACT:
E-mail:		fmigroup@maplesoft.com
Website:	https://www.maplesoft.com
