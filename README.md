# Modeling Adhesive Interactions Between Tumor Cells and Endothelial Cells
**2020 UWM SURF Research Symposium** · John Quinn · Mentor: Dr. Mahsa Dabagh, Biomedical Engineering

🏆 **Department Award, UWM College of Engineering & Applied Science Student Research Poster Competition (2020)**
for this undergraduate research ([Dabagh Lab news](https://sites.uwm.edu/dabaghlab/))

## Links
- [Symposium page with Video and Abstract](https://sites.uwm.edu/undergrad-research-symposium/2020/04/22/modeling-of-adhesive-interactions-between-tumor-cells-and-endothelial-cells/)

## Summary
This project couples the molecular dynamics package LAMMPS with the fluid dynamics
package Palabos to model circulating cancer cells, other blood components (red and
white blood cells, plasma) and their adhesive interactions with the endothelial cells
lining the arterial wall. The goal is a better understanding of the mechanisms behind
cancer metastasis. The same approach could extend to other blood-flow disorders, such
as sickle cell anemia.

This work became the foundation for my MS thesis, *Modeling of Circulating Cancer
Cells Subjected to Arterial Flow Conditions* (UW–Milwaukee, 2025)

## Full Abstract

Computer simulation has been a growing field, driven in large part by the increase in computing power easily available. One way to harness this power is to simulate that which we cannot easily analyze in the real world, in this case the possible interactions that simulated cancer cells may have with other blood components (red blood cells, white blood cells and plasma) or other surfaces that may come into contact with blood flow such as arterial walls, endothelial cells lining the arterial wall, and common implanted biomaterials. This will be done by using the molecular dynamic simulation software LAMMPS and fluid dynamics simulation software Palabos to model these interactions. These have been coupled before and their coupling has been validated with real world data, however our study goes a few steps further by simulating other possible blood components as well as the titular cancer cells and the other surfaces that blood may contact. The objective of our study is to couple LAMMPS and Palabos to model the circulation and its adhesive interactions with endothelial cells of the arterial wall. The important outputs of the simulations may be an increased understanding of how cancer cell interactions within the blood thus gaining a better knowledge of mechanisms underlying the cancer metastasis. Finally if this behavior can be understood better using these programs there may be new treatments that could be developed based on this data, and similar techniques used in this study may be applied to other disorders affecting blood flow such as sickle cell anemia (model the sickle cells) or maybe the uptake of glucose in diabetic patients may be modeled.


## Contents
| File / folder | What it is |
|---|---|
| [CEAS Poster.pdf](CEAS%20Poster.pdf) | Research poster from the CEAS Student Research Poster Competition |
| [Molecular Dynamics Simulation of Blood Flow done.pptx](Molecular%20Dynamics%20Simulation%20of%20Blood%20Flow%20done.pptx) | Slides for the SURF symposium presentation |
| [References-lammps-4-14-2020.docx](References-lammps-4-14-2020.docx) | Reference list for the project |
| [Simple LAMMPS Sim Pic.PNG](Simple%20LAMMPS%20Sim%20Pic.PNG) | Screenshot of a simple LAMMPS simulation |
| [JQ - Random/](JQ%20-%20Random/) | Example LAMMPS simulation shown in the presentation: a periodic box of randomly placed Lennard-Jones particles |
| [JQ - Random/JQ-Random.py](JQ%20-%20Random/JQ-Random.py) | Python script that generates 1,000 random atom positions in a 100 × 100 × 100 box and writes the LAMMPS data file |
| [JQ - Random/JQ-Random.data](JQ%20-%20Random/JQ-Random.data) | LAMMPS data file produced by the Python script |
| [JQ - Random/in.JQ-random](JQ%20-%20Random/in.JQ-random) | LAMMPS input script: reads the data file, removes overlapping atoms, and runs 1,000 timesteps with an NPT fix |
| [JQ - Random/dump.JQ-random](JQ%20-%20Random/dump.JQ-random) | Trajectory output (positions and velocities every 10 steps) |
| [JQ - Random/log.lammps](JQ%20-%20Random/log.lammps) | LAMMPS log from the run |
| [JQ - Random/JQ-Random-Movie.mp4](JQ%20-%20Random/JQ-Random-Movie.mp4) | Animation rendered from the trajectory |

## Tools
[LAMMPS](https://www.lammps.org) · [Palabos](https://palabos.unige.ch) · [Python](https://www.python.org)

## License
The code in this repository is released under the [GNU General Public License v2.0](LICENSE)
