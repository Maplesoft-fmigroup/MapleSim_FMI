Description:
CoupledClutches example from the FMI test suite - Array of 4 outputs

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
fmusim --interface-type cs --stop-time 1.5 --input-file CoupledClutches_in.csv --output-file CoupledClutchesCS.csv CoupledClutches.fmu 
fmusim --interface-type me --stop-time 1.5 --input-file CoupledClutches_in.csv --output-file CoupledClutchesME.csv CoupledClutches.fmu 

CONTACT:
E-mail:		fmigroup@maplesoft.com
Website:	https://www.maplesoft.com
