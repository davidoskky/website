---
title: "Python Libraries for chemistry"
date: 2024-07-11
draft: false
---

Python is a powerful programming language widely used in various scientific fields, including chemistry. The versatility and efficiency of Python have led to the development of numerous libraries tailored for chemical data manipulation. These libraries assist in everything from cheminformatics to molecular dynamics and quantum chemistry. Below is an incomplete list of Python libraries that can be used to manipulate different types of chemical data and perform different kinds of operations and calculations.



### Cheminformatics

{{< table "table table-striped table-bordered" >}}
| Library         | License      | Description                               |
|-----------------|--------------|-------------------------------------------|
| RDKit           | Open Source  | Cheminformatics tools for molecular modeling. |
| Openeye         | Proprietary  | Tools for cheminformatics and molecular modeling. |
| Pybel           | Open Source  | Python wrapper for the Open Babel toolkit. |
| MolVS           | Open Source  | Standardization and validation of chemical structures. |
| ESPsim          | MIT          | Shape and electrostatic similarities of molecules. |
| ScaffoldGraph   | MIT          | Generation and analysis of molecular scaffold networks. |
| reaction-network| Open Source  | Synthetic planning and reaction pathway prediction. |
| xyz2graph       | MIT          | Visualization of XYZ files and reconstruction of the molecular graph. |
| Matcher         | MIT          | UI to identify modifications that improved a drug. |
| FPSim2          | MIT          | Fast fingerprint-based molecular similarity. |
| usearch-molecules| Apache2     | Molecular similarity and clustering based on fingerprints. |
| PatentChem      | MIT          | Searches USPTO for patented molecules. |
| Metgem          | GPL3         | Molecular networks generation. |
| pyADA           | GPL3         | Compute applicability domain of ML models. |
{{< /table >}}


### Molecular Dynamics

{{< table "table table-striped table-bordered" >}}
| Library       | License      | Description                               |
|---------------|--------------|-------------------------------------------|
| MDAnalysis    | Open Source  | Analyzing molecular dynamics trajectories. |
| OpenMM        | Open Source  | High-performance molecular dynamics simulations. |
| BioSimSpace   | GPL3         | Interface to several MD engines. |
| PyContact     | GPL3         | Analysis of non-covalent interactions in MD. |
{{< /table >}}

### Macromolecules

{{< table "table table-striped table-bordered" >}}
| Library      | License      | Description                               |
|--------------|--------------|-------------------------------------------|
| Gemmi        | Open Source  | Macromolecules, 3D structures, molecular dynamics, format conversion. |
| Biopython    | Open Source  | Tools for biological computation. |
| Pyrosetta    | Academic License | Interface to Rosetta for macromolecular modeling. |
| PDBFixer     | Open Source  | Preparing PDB files for molecular simulations. |
| ChemLab      | GPL3         | Macromolecular visualization and system preparation. |
| QCEngine     | BSD3         | Standardized interface for several QC and MM engines. |
| Panel-Chemistry | MIT       | Visualization of molecules for building interfaces. |
{{< /table >}}

### Machine Learning

{{< table "table table-striped table-bordered" >}}
| Library           | License      | Description                               |
|-------------------|--------------|-------------------------------------------|
| DeepChem          | Open Source  | Machine learning tools for drug discovery and quantum chemistry. |
| ChemML            | Open Source  | Machine learning for chemical research. |
| Chemprop          | Open Source  | Machine learning for property prediction. |
| TorchANI          | Open Source  | Machine learning potentials for quantum chemistry. |
| Molfeat           | Apache2      | Molecular encodings for deep learning. |
| ASAPDiscovery     | MIT          | Framework for antiviral drug discovery. |
| Therapeutics Data Commons | MIT  | Datasets and benchmarks for drug discovery AI. |
| ChemicalX         | Apache2      | Drug-drug interaction prediction. |
| Reinvent          | Apache2      | Molecule generation and scoring framework. |
| Foundry           | MIT          | Data preparation for machine learning. |
| AMPL              | MIT          | Automatic construction of ML predictive models. |
| Matbench          | MIT          | Benchmarking machine learning for materials. |
| pumml             | MIT          | Classify molecules with only positive data. |
{{< /table >}}

### Quantum Chemistry

{{< table "table table-striped table-bordered" >}}
| Library       | License      | Description                               |
|---------------|--------------|-------------------------------------------|
| PySCF         | Open Source  | Quantum chemistry tools. |
| Psi4          | LGPL3        | Ab initio quantum chemistry simulations. |
| VASPy         | MIT          | Manipulates and visualizes VASP data. |
| QMFlows       | LGPL3        | Quantum chemistry workflows. |
| Quacc         | BSD3         | Workflow manager for quantum calculations. |
| GeomeTRIC     | BSD3         | Geometry optimization of molecules. |
| Psikit        | BSD3         | Integrates Psi4 and RDKit. |
{{< /table >}}

### Format Conversion

{{< table "table table-striped table-bordered" >}}
| Library      | License      | Description                               |
|--------------|--------------|-------------------------------------------|
| ParmEd       | LGPL         | Molecular mechanics parameter file editor. |
| CDPKit       | LGPL         | Cheminformatics and format conversion. |
{{< /table >}}

### Free Energy

{{< table "table table-striped table-bordered" >}}
| Library      | License      | Description                               |
|--------------|--------------|-------------------------------------------|
| OpenFE       | Open Source  | Free energy calculations in molecular dynamics. |
| Lomap        | MIT          | Free energy calculations. |
| Alchemlyb    | BSD3         | Automate alchemical free energy analysis. |
{{< /table >}}

### Molecular Mechanics

{{< table "table table-striped table-bordered" >}}
| Library      | License      | Description                               |
|--------------|--------------|-------------------------------------------|
| ASE          | Open Source  | 3D structure manipulation and atomistic simulations. |
| OpenFF       | MIT          | Molecular mechanics and force fields. |
| ACPYPE       | GPL3         | Interface to Antechamber for Amber. |
| Chemcoord    | LGPL3        | Manipulate cartesian and internal coordinates. |
| maml         | BSD3         | Materials simulations. |
{{< /table >}}		

### Thermodynamics

{{< table "table table-striped table-bordered" >}}
| Library      | License      | Description                               |
|--------------|--------------|-------------------------------------------|
| Thermo       | MIT          | Thermodynamic properties calculation. |
| Sella        | LGPL3        | Identify saddle points in thermodynamics. |
{{< /table >}}

### Analytical Chemistry

{{< table "table table-striped table-bordered" >}}
| Library         | License      | Description                               |
|-----------------|--------------|-------------------------------------------|
| SpectroChemPy   | Free Software| Process and analyze spectrographic data. |
{{< /table >}}

### Databases

{{< table "table table-striped table-bordered" >}}
| Library               | License      | Description                               |
|-----------------------|--------------|-------------------------------------------|
| Mendeleev             | MIT          | Periodic table information. |
| Therapeutics Data Commons | MIT      | Datasets and benchmarks for drug discovery AI. |
| usearch-molecules     | Apache2      | Molecular similarity and clustering based on fingerprints. |
| PatentChem            | MIT          | Searches USPTO for patented molecules. |
{{< /table >}}

### Automated Design

{{< table "table table-striped table-bordered" >}}
| Library        | License      | Description                               |
|----------------|--------------|-------------------------------------------|
| Reinvent       | Apache2      | Molecule generation and scoring framework. |
| stk            | MIT          | Structural data manipulation and molecular design. |
{{< /table >}}

### Visualization

{{< table "table table-striped table-bordered" >}}
| Library         | License      | Description                               |
|-----------------|--------------|-------------------------------------------|
| Panel-Chemistry | MIT          | Visualization of molecules for building interfaces. |
| xyz2graph       | MIT          | Visualization of XYZ files and reconstruction of the molecular graph. |
{{< /table >}}

### File Format

{{< table "table table-striped table-bordered" >}}
| Library       | License     | Description                |
| ------------- | ----------- | -------------------------- |
| Chemical JSON | Open Source | Chemical JSON file format. |
{{< /table >}}

### ADMET

{{< table "table table-striped table-bordered" >}}
| Library         | License      | Description                               |
|-----------------|--------------|-------------------------------------------|
| ChemicalX       | Apache2      | Drug-drug interaction prediction. |
{{< /table >}}
