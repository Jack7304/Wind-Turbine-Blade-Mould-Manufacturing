# Wind Turbine Blade and Mold CAD Models

## Overview

This repository provides a complete set of CAD models for a horizontal-axis wind turbine rotor system, including:

* Complete wind turbine rotor assembly
* Individual turbine blade model
* Blade mold model for manufacturing
* STL files for 3D printing
* STEP files for CAD modification and engineering analysis

The models are suitable for:

* Wind energy education
* CAD design practice
* 3D printing projects
* CFD simulations
* Structural analysis
* Composite blade manufacturing studies
* Rapid prototyping

---

## Model Description

### Rotor Assembly

The rotor assembly contains all blades positioned around the hub to form a complete wind turbine rotor.

Applications:

* Wind turbine visualization
* Aerodynamic demonstrations
* Educational projects
* System-level simulations

---

### Blade Model

The blade model is provided as a standalone component.

Applications:

* CFD analysis
* Structural optimization
* Airfoil studies
* Parametric redesign
* Finite Element Analysis (FEA)

---

### Blade Mold Model

The mold model is designed for blade manufacturing and prototyping.

Applications:

* Composite manufacturing research
* Mold design studies
* Production planning
* Rapid tooling development

---

## File Formats

### STL Files

STL models are intended for:

* 3D printing
* Mesh-based simulations
* Rapid prototyping

Compatible software:

* Bambu Studio
* Cura
* PrusaSlicer
* OrcaSlicer
* MeshLab

---

### STEP Files

STEP models preserve CAD geometry and can be edited directly.

Compatible software:

* Autodesk Fusion 360
* Onshape
* SolidWorks
* CATIA
* Siemens NX
* Creo
* FreeCAD

---

## Usage Guide

### Option 1: 3D Printing

1. Open the STL file in your preferred slicer software.
2. Scale the model if required.
3. Configure printing parameters:

   * Layer Height: 0.20 mm
   * Infill: 15–30%
   * Wall Count: 3–4
4. Generate G-code.
5. Print the model.

Recommended software:

* Bambu Studio
* OrcaSlicer
* Cura

---

### Option 2: CAD Modification

1. Open the STEP file in a CAD platform.
2. Import the geometry.
3. Modify dimensions, blade shape, or assembly features.
4. Export as STEP, STL, or other CAD formats.

Recommended software:

* Fusion 360
* Onshape
* SolidWorks

---

### Option 3: Engineering Analysis

The blade model can be imported into:

* ANSYS
* Abaqus
* COMSOL Multiphysics
* OpenFOAM

Typical workflows:

1. Import STEP geometry.
2. Generate mesh.
3. Define material properties.
4. Apply aerodynamic or structural loads.
5. Run simulation and evaluate performance.

---

## Recommended Workflow

### For Makers

```text
STL → Bambu Studio → Slice → Print
```

### For CAD Designers

```text
STEP → Fusion 360 / Onshape → Modify → Export
```

### For Engineers

```text
STEP → ANSYS / OpenFOAM → Analysis
```

---

## Applications

* Renewable energy education
* Wind turbine prototyping
* Mechanical design practice
* CFD research
* Structural analysis
* Composite manufacturing studies
* Additive manufacturing projects

---

## License

This project is released under the MIT License.

You are free to:

* Use
* Modify
* Distribute
* Share

with proper attribution.

---

## Author

Created and maintained by Zhao Yuxuan.

Focus Areas:

* CAD Design
* Fusion 360
* Onshape
* MATLAB
* Python
* Engineering Open-Source Projects

If you encounter technical issues or have suggestions for improvement, feel free to open an issue or contact me.
