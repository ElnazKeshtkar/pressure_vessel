# Pressure Vessel Stress Analysis (FEA)

This project performs a static structural analysis on a pressure vessel to evaluate its integrity under operational loads, following standard engineering practices and ASME guidelines.

## Project Overview
The primary objective of this study is to determine the stress distribution and total deformation of the pressure vessel when subjected to internal pressure and gravity loads.

## Methodology
- **CAD Modeling:** The pressure vessel was designed in **SolidWorks**, including nozzles, lifting lugs, and supporting saddles.
- **Finite Element Analysis (FEA):** Conducted in **Ansys Workbench**.
- **Meshing:** Implemented `Mesh Refinement` at critical areas, such as nozzle-to-shell connections and supports, to ensure accurate stress concentration capture.
- **Boundary Conditions:**
    - Internal Pressure: 10 MPa.
    - Gravity Load: `Standard Earth Gravity` to account for self-weight.
    - Supports: `Fixed Support` applied to the saddles to simulate real-world installation conditions.

## Results
The analysis highlights the stress concentration areas and total deformation of the vessel.

### Total Deformation
![Total Deformation](images/total_deformation.png)

### Equivalent (Von-Mises) Stress
![Equivalent Stress](images/equivalent_stress.png)

## Technical Highlights
- **Validation:** Results were validated by comparing Ansys outputs with theoretical stress calculations (Hoop and Longitudinal stresses).
- **Refinement:** Performed mesh refinement to optimize the balance between computational cost and result accuracy.
- **Safety Assessment:** The maximum stress values were evaluated against the material's yield strength to ensure the design is within safe limits.

---
*Created by: Elnaz Keshtkar*