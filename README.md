<!-- HTML approach -->
<img src="https://github.com/Maplesoft-fmigroup/MapleSim_FMI/blob/main/Maplesoft_logo.png"  width="200"/>

# [MapleSim](https://www.maplesoft.com/products/maplesim)
MapleSim is an advanced modeling and simulation tool that helps you reduce development time, lower costs, and diagnose real-world performance issues.

*******************************************************************************************
Please report any failure, report an issue or send your comments or suggestions to fmigroup@maplesoft.com
*******************************************************************************************

# FMI Export Compatibility Information
All of the FMUs linked below have been exported by latest released version of MapleSim. All of the FMUs contain multi-platform binaries (windows64, linux64, darwin64). Consult Readme.txt of an FMU for more detailed information.  Additional platform binaries can be provided upon request.


## Validation tools
- FMPy 0.3.16
- FMUChecker-2.0.4

<details open>
<summary> MapleSim 2023 </summary>

| **Model Name** | **FMI2.0** |  **FMI3.0** | 
| :--- | --- | --- |
| ControlledTemperature | [CS](https://github.com/Maplesoft-fmigroup/MapleSim_FMI/tree/main/MapleSim_2023/FMI_Export/FMI_2/CS/ControlledTemperature/ControlledTemperature.fmu), [ME](https://github.com/Maplesoft-fmigroup/MapleSim_FMI/tree/main/MapleSim_2023/FMI_Export/FMI_2/ME/ControlledTemperature/ControlledTemperature.fmu)| [CS/ME] |
| CoupledClutches | [CS](https://github.com/Maplesoft-fmigroup/MapleSim_FMI/tree/main/MapleSim_2023/FMI_Export/FMI_2/CS/CoupledClutches/CoupledClutches.fmu), [ME](https://github.com/Maplesoft-fmigroup/MapleSim_FMI/tree/main/MapleSim_2023/FMI_Export/FMI_2/ME/CoupledClutches/CoupledClutches.fmu)| [CS/ME] |
| Rectifier | [CS](https://github.com/Maplesoft-fmigroup/MapleSim_FMI/tree/main/MapleSim_2023/FMI_Export/FMI_2/CS/Rectifier/Rectifier.fmu), [ME](https://github.com/Maplesoft-fmigroup/MapleSim_FMI/tree/main/MapleSim_2023/FMI_Export/FMI_2/ME/Rectifier/Rectifier.fmu)| [CS/ME] |
</details>

# FMI Import Compatibility Information

These FMUs have been tested successfully in the most recent release of MapleSim.

## Exporting tool:

<details>
<summary> Dymola </summary>


### [Dymola (2019FD01)](https://github.com/modelica/fmi-cross-check/tree/master/fmus/2.0/cs/win64/Dymola)

| **FMI-2.0** | **win64** | 
| :--- | --- |
| BooleanNetwork1 | ME, CS |
| ControlledTemperature | ME, CS |
| CoupledClutches | ME, CS |
| DFFREG | ME, CS |
| IntegerNetwork1 | ME, CS |
| Rectifier | ME, CS |

</details>

<details>
<summary> FMUSDK </summary>


### [FMUSDK (2.0.4)](https://github.com/modelica/fmi-cross-check/tree/master/fmus/2.0/cs/win64/FMUSDK)

| **FMI-2.0** | **win64** | 
| :--- | --- |
| BouncingBall | ME, CS |
| dq | ME, CS |
| inc | ME, CS |
| vanDerPol | ME, CS |

</details>

<details>
<summary> SimulationX </summary>


### [SimulationX (4.0.4)](https://github.com/modelica/fmi-cross-check/tree/master/fmus/2.0/cs/win64/SimulationX)

| **FMI-2.0** | **win64** | 
| :--- | --- |
| ControlledTemperature | ME, CS |
| CoupledClutches | ME, CS |
| DoublePendulum | ME, CS |

</details>
