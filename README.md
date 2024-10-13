# Conference-IBPC2024-Humidity-Case

Solver used in this case can be found in https://github.com/Eddy3D-Dev/humidityRhoThermo.

## Steps to compile the updated solver


Clone the repository to any place you want using the following command:
```console
@-: git clone https://github.com/Eddy3D-Dev/humidityRhoThermo.git
```

After that load your OpenFOAM environment (if not already happend) and move into the repository. Here checkout your version you want:
```console
@~: git checkout OpenFOAM-v9
```
After you switched to your OpenFOAM version, you compile the updated solver:
```console
@~: Allwmake
```
You are done. After that, you can use the updated buoyantHumidityPimpleFoam solver.
