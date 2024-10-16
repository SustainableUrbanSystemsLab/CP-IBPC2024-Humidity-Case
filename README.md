# Conference-IBPC2024-Humidity-Case

# How much computational complexity is necessary to model relevant aspects in microclimate urban physics?


# Abstract

Accurate microclimate data obtained through observation or CFD models is crucial for urban design and environmental improvements. Eddy3D is one of the tools widely used for simulating microclimate conditions. However, the tool currently lacks the incorporation of relevant urban physics into the simulation. The present research focuses on integrating the modeling of convective heat transfer and relative humidity within the Eddy3D wind module and unsteady state modeling. The study reports the approaches through simulations employing a simplified canyon model. The study site is the campus of the Toronto Metropolitan University in Toronto, Ontario. The simulation data is validated using real-time data collected from the weather station located on the roof of one of the buildings on the downtown campus. By comparing the simulated data with the real-time data, the study assesses the effectiveness of the new features and determines their appropriateness for integration into the Eddy3D tool. The findings highlight the adaptability and accuracy of the approach across various scenarios, effectively handling complex modeling to enhance the capabilities of microclimate predictions.

# Keywords

```Urban Micro-climate, urban heat island, CFD, Urban building energy modeling```

# Author

- Name: [Sina Rahimi](mailto:sina.rahimi@torontomu.ca)
- LinkedIn: [Link](https://www.linkedin.com/in/sinarahimi2020/)
- Institution: Toronto Metropolitan University
- Program: PhD Building Science
- Advisors: Dr. Umberto Berardi, Dr. Patrick Kastner

#Repository Structure

- tutorial/: Directory containing the case study used in the research.
- Resources/: Directory containing weather station data used in the research.
- README.md: This file, providing an overview of the research and repository.

# Instructions for running the case


1-      **Compile the solver***

** Steps to compile the updated solver***

Clone the repository to any place you want using the
the following command:

```console
@-: git clone https://github.com/Eddy3D-Dev/humidityRhoThermo.git
```

After that, load your OpenFOAM environment (if it has not already
happened) and move it into the repository. Here, check your version you want:

```console
@~: git checkout OpenFOAM-v9
```

After you switch to your OpenFOAM version, you compile the
updated solver:

```console
@~: Allwmake
```

You are done. After that, you can use the updated **buoyantHumidityPimpleFoam* solver.

2-      **Run the test case**

Clone the repository to any place you want using the
the following command:

```console
@-: git clone https://github.com/SustainableUrbanSystemsLab/CP-IBPC2024-Humidity-Case/tree/main/tutorial.git
```

After that, load your OpenFOAM environment (if it has not already happened) and move it into the repository. Here, check your version you want:

```console
@~: git checkout OpenFOAM-v9  
```
```console
@~: Allprepare
```

Note that you can change the mesh settings by changing
parameters of sanppyhexmeshDict in the system folder.

# Citation

```console
@confpaper{
  title = {How much computational complexity is necessary to model relevant aspects in microclimate urban physics?},
  author = {Rahimi, Sina},
  year = {2024},
  school = {Toronto Metropolitan University},
  type = {Conference Paper}
}
```
# Source

[Link](https://github.com/SustainableUrbanSystemsLab/CP-IBPC2024-Humidity-Case) to this repository.
