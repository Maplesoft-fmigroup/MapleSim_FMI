Description:
CoupledClutches example from the FMI test suite

FMI Type:
CoSimulation

Platform:
win64, linux64, darwin64

Compilers:
gcc on linux64 and darwin64
clang on win64

Validation Tools:
FMUChecker-2.0.4
FMPy 0.3.19
fmusim b20ed8c (x86_64-linux)

Command to reproduce:
fmusim --stop-time 1.5 --output-interval 0.01 --input-file CoupledClutches_in.csv --output-file CoupledClutches.csv CoupledClutches.fmu

CONTACT:
E-mail:		fmigroup@maplesoft.com
Website:	https://www.maplesoft.com
