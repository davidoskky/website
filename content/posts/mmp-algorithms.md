---
title: Introduction to Matched Molecular Pairs Algorithms
date: 2024-07-11
draft: false
---
Matched Molecular Pair (MMP) analysis has become a useful tool for examining and optimizing the properties and potency of compounds. Introduced by Kenny and Sadowski in 2005, an MMP consists of a pair of compounds that differ by a small, localized change, known as a transformation, while retaining the same maximum common substructure (MCS). This analysis helps correlate these structural changes with property alterations, such as biological activity, thereby facilitating the rationalization of structure-property relationships (SPR).

MMP analysis is widely used in several areas of drug discovery and development:

- **ADMET Optimization**: Helps understand how structural changes affect a compound's absorption, distribution, metabolism, excretion, and toxicity (ADMET) profile.
- **Selectivity Improvement**: Aids in enhancing ligand selectivity towards specific targets.
- **Structure-Activity Relationship (SAR) Analysis**: Assists in determining the impact of small molecular changes on biological activity.
- **De Novo Drug Design**: Supports the design of new compounds using methodologies like BRADSHAW and models such as DeepSARM.
- **Detection of Activity Cliffs**: Identifies significant changes in compound properties, providing valuable insights for improvement.

### Advantages and Limitations

**Advantages:**

- **Insightful Analysis**: MMP analysis offers valuable insights into how small structural changes impact compound properties, aiding in rational drug design and optimization.
- **Broad Applicability**: MMP analysis can be applied across various stages of drug development, from hits up to ADMET optimization.

**Limitations:**

- **Generalization Issues**: The effects of chemical substitutions may not always be generalizable across different molecular contexts.
- **Data Dependencies**: The accuracy and reliability of MMP analysis are heavily dependent on the quality and context of the molecular data used.
- **Additivity Assumption**: MMP analysis often assumes additive effects of substituents, which may not hold true in non-linear structure-activity relationship cases.
- **Context Dependence**: The effects of structural changes can vary significantly depending on the molecular context, making it challenging to generalize findings across different compounds and datasets.

### Algorithms for MMP Analysis

Various algorithms have been developed to identify and analyze MMPs:

1. **Predefined Transformation**: Uses a set of predefined rules to identify MMPs. Examples include RECAP and Drug Guru. These are easy to implement and fast but limited by predefined transformation catalogs.
2. **Maximum Common Substructure (MCS)-based**: Uses clique detection to identify the MCS between pairs of molecules. WizePairZ is an example. While capable of discovering novel transformations, these methods are computationally intensive.
3. **Fragmentation and Indexing (F+I)**: Proposed by Hussain and Rea in 2010, this method involves fragmenting molecules, indexing the fragments, and identifying commonalities. It is way more efficient than MCS-based methods can slow down with large datasets. This is the current standard technique used for MMPA.

Additional properties beyond the specific transformation can be included, such as the local topology of the molecule, which helps determine when a specific MMP may be applicable, thus attempting to generate an applicability domain of the transformation. Including information about the surrounding of the molecule, such as protein residues in contact with the transformed segment when 3D information is available, further enhances the analysis.
### VAMMPIRE

The VAMMPIRE (Virtually Aligned Matched Molecular Pairs Including Receptor Environment) database exemplifies the application of MMP analysis in structure-based drug design and optimization. This database (now unavailable) generated MMPs using the fragmentation approach and analyzed how different molecular substitutions affect the binding affinity of ligands within specific protein environments including data of the 4 nearest protein residues to the ligand with data obtained from the PDB and from docking.

### Working with MMPs

Currently, no high-end library for working with MMPs exists. The most comprehensive one is mmpdb, an evolution of the original MMPA developed by Hussain and Rea. Matcher, a software developed by Merck, offers a frontend to mmpdb and adds some search algorithms.

### Application in Drug Design

Methodologies like BRADSHAW, fragment-based structure generation frameworks, and deep learning architectures such as DeepSARM are employed in de novo drug design. Recently, the model Mol2Mol has been published and integrated into REINVENT4. This model, trained on a large set of MMPs, promises to be able to exhaustively explore the chemical space around a lead, although more evidence is needed to fully support this claim.