# axial-pmsg-digital-twin
Hybrid Statistical Modeling of an Axial-Flux PMSG

# Data-Driven Digital Twin Framework for Axial-Flux PMSGs

This repository contains the replication code and datasets developed for the statistical optimization and filtering of electromagnetic variables in axial-flux Permanent Magnet Synchronous Generators (PMSGs). This framework serves as the core methodology for baseline characterization (9-slot, 8-pole topology) and its subsequent expansion toward multiphase (3-phase and 7-phase) machine digital twins.

## 🛠️ Methodology Overview
* **Experimental Data Acquisition:** Initial characterization conducted using a manual variable-speed mechanical drive (hand drill) coupled to the rotor shaft, evaluating rectifier stage dynamics up to ~65V DC.
* **Anomaly Detection:** Implementation of Interquartile Range (IQR) filtering to isolate stochastic human-induced mechanical fluctuations from pure electromagnetic behavior.
* **Regression Modeling:** Physics-informed deterministic linear tracking to map rotational speed (RPM) against induced voltage components.

## 📂 Repository Structure
* `/src`: Contains the original Python/Google Colab notebooks (`.ipynb`) used during exploratory data analysis and model training.
* `/data`: Sample hybrid datasets containing experimental measurements under non-ideal mechanical inputs.

## 🎓 Academic Credit
This development originated as part of a Master's Thesis in Data Analysis and is currently being extended for PhD-level validation of multiphase axial-flux machines.
