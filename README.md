# Ion Beam Targeting Optimization using Machine Learning

## 🧪 Project Overview
Precise control of ion-beam trajectories is critical in accelerator physics experiments, where even small misalignments can cause the beam to impact surrounding structures instead of the intended target.

In this project, experimental data from the LEMA accelerator at IFUNAM was analyzed to study the implantation of Se-80 and Se-82 isotopes into a carbon target coated with a thin gold layer.

During the experiment, part of the ion beam impacted the aluminum frame surrounding the target, reducing implantation efficiency and potentially affecting experimental outcomes.

To address this issue, the project combines numerical modeling and machine learning to classify beam trajectories and identify whether the beam impacts:

- the intended target region, or

- the surrounding aluminum frame.

## 🎯 Objective

Develop a machine learning classifier capable of predicting whether a given beam trajectory will correctly hit the target or spill over to the surrounding structure.

This enables:

- improved beam alignment

- better experimental efficiency

- data-driven optimization of accelerator parameters

## 🧠 Methodology

### Physical Modeling

Beam trajectories were first modeled using a numerical formulation inspired by the goat grazing problem, which describes constrained motion within bounded geometries.

This provided a mathematical representation of the beam–target interaction region.

### A Logistic Regression classifier was trained to predict the beam impact location.

## 📊 Key results

The model successfully distinguishes between:

- trajectories hitting the target

- trajectories impacting the aluminum frame

This provides a practical tool for beam diagnostics and experimental optimization.

## 🛠️ Technologies

- Python

- NumPy

- Pandas

- Scikit-Learn

- Matplotlib / Seaborn

## 💡 Key Skills Demonstrated

- Physics-informed machine learning

- Classification modeling

- Scientific data analysis

- Experimental diagnostics


## 🖼️ Results Preview

![Prediction Preview](https://github.com/lvalencia232/Ion-Beam-Targeting-Optimization-with-ML/blob/main/images/model_pred.png)
![Diagram Preview](https://github.com/lvalencia232/Ion-Beam-Targeting-Optimization-with-ML/blob/main/images/diagram.png)
