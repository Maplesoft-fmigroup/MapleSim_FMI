Description:
ControlledTemperature example from the FMI test suite
(with Directional Derivatives)

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
fmusim --stop-time 10 --output-interval 0.02 --output-file ControlledTemperature.csv ControlledTemperature.fmu

CONTACT:
E-mail:		fmigroup@maplesoft.com
Website:	https://www.maplesoft.com
