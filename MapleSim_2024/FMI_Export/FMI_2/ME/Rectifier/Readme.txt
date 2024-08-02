Description:
Rectifier example from the FMI test suite

FMI Type:
ModelExchange

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
fmusim --stop-time 0.1 --output-interval 0.0002 --solver cvode --tolerance 1e-5 --output-file Rectifier.csv Rectifier.fmu

CONTACT:
E-mail:		fmigroup@maplesoft.com
Website:	https://www.maplesoft.com
