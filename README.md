# Beam–Target Interaction Analysis for Isotopic Implantation Optimization

## Descripción del Proyecto
Precise control of ion-beam trajectories is essential in nuclear and materials physics experiments, particularly when producing isotopically pure targets for further analysis.

In this project, an experimental campaign was conducted to implant Se-80 and Se-82 isotopes into a carbon target coated with a thin gold layer, mounted on an aluminum frame. The experiment was performed using the LEMA accelerator at IFUNAM, and the target 
was fully characterized both before and after implantation.

During the experiment, it was observed that the generated ion beam did not exclusively impact the intended target region, but partially struck the surrounding aluminum frame. This issue, previously identified in accelerator physics, was addressed
through a numerical solution to the “goat grazing problem”, which describes constrained beam trajectories within bounded geometries.

Building upon this numerical framework, a machine learning–based classification model is proposed to:

- identify the fraction of the beam impacting the aluminum frame,

- distinguish it from the portion correctly hitting the target,

- and support beam optimization and alignment strategies.

The project demonstrates:

- integration of experimental accelerator physics with computational modeling,

- application of machine learning to beam diagnostics,

- interpretation of ML outputs in a physical and geometrical context,

- optimization-oriented thinking applied to real experimental constraints.

This repository highlights how machine learning techniques can complement numerical physics solutions to improve experimental design and accelerator performance.
