# # JP-BE2025-Humidity-Case

<style>
</style>

**Incorporating Convective Heat Transfer and Humidity Effects in Urban Microclimate Modeling: Should we care?****?**

![](C:\Users\engsi\AppData\Roaming\marktext\images\2025-04-15-18-25-11-image.png)



**Abstract**

ccurate microclimate data, obtained through observation or CFD models, is crucial for urban design and environmental improvements. One approach to quantifying microclimate conditions involves the use of isothermal CFD simulations combined with convective heat transfer and relative humidity modeling, implemented via the buoyantHumidityPimpleFoam solver in OpenFOAM. This research investigates the additional complexity when incorporating these factors into unsteady-state modeling for urban microclimate simulations. This study reports the approaches through simulations employing a simplified canyon model. The study site is the campus of the Toronto Metropolitan University campus in Toronto, Ontario, Canada. The simulation data is validated using real-time data collected from the weather station located on the roof of one of the buildings on the downtown campus. By comparing the simulated data with real-time observations, the study assesses the effectiveness of the new features and evaluates their suitability for integration into existing urban microclimate modeling frameworks. The results show that adding humidity not only improves the model realism but also greatly increases its ability to predict complex urban microclimate dynamics. These findings highlight the importance of this approach for applications such as thermal comfort optimization, public health planning, and climate resilience strategies, demonstrating its potential to advance urban microclimate simulations.

**Keywords**

Urban Micro-climate, urban heat island, CFD, Urban building
energy modeling

**Author**

- Name: Sina Rahimi (hyper to email)
- LinkedIn: link
- Institution: Toronto Metropolitan University
- Program: Building Scinece
- Advisors: Dr. Patrick Kastner, Dr. Umberto Berardi

**Repository Structure**

- tutorial/: Directory containing the case study used in the research.
- Resources/: Directory containing weather station data used in the research.
- README.md: This file, providing an overview of the research and repository.

**Instructions for reconstructing mesh geometry in Jupyter
Notebook**

1-      **Compile the solver***

** Steps to compile the updated solver***

Clone the repository to any place you want using the
following command:

```console
@-: git clone
https://github.com/SustainableUrbanSystemsLab/humidityRhoThermo.git
```

After that load your OpenFOAM environment (if not already
happend) and move into the repository. Here checkout your version you want:

```console
@~: git checkout OpenFOAM-v9
```

After you switched to your OpenFOAM version, you compile the
updated solver:

```console
@~: Allwmake
```

You are done. After that, you can use the updated **buoyantHumidityPimpleFoam* solver.

2-      Run the test case

Clone the repository to any place you want using the
following command:

```console
@-: git clone
https://github.com/SustainableUrbanSystemsLab/JP-BE2025-Humidity-Case.git
```

After that load your OpenFOAM environment (if not already happend) and move into the repository. Here checkout your version you want:

```console
@~: git checkout OpenFOAM-v9  

```console

@~: Allprepare
```

Note that you can change the mesh settings by changing
parameters of sanppyhexmeshDict in the sytsem folder.

**Citation**

Please cite our work if you decide to use this for your own research.

**APA**

```
Rahimi, S., Kastner, P., & Berardi, U. (2025). Incorporating convective heat transfer and humidity effects in urban microclimate modeling: Should we care? Building and Environment, 276, 112858. https://doi.org/https://doi.org/10.1016/j.buildenv.2025.112858.
```

**Bibtex**

@confpaper{

  title = {Incorporating convective heat transfer and humidity effects in urban microclimate modeling: Should we care?},

  author = {Rahimi, Sina}, {Patrik Kastner}, {Umberto Berardi}

  year = {2025},

  school = {Toronto Metropolitan University},

  type = {Journal Paper}

**Source**

[https://www.sciencedirect.com/science/article/pii/S0360132325003403](Link) to the paper.
