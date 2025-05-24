# Bio3D

This repository provides basic usage examples of the **Bio3D** R package for structural bioinformatics.

## Overview

The repository is organized into two main folders: `scripts` and `example`.

### `scripts/` — Core Bio3D Demos

This folder contains four demo scripts that showcase fundamental functionalities of the Bio3D package:

- **Reading PDB files** (single and multiple)  
- **Atom, residue, and chain selection**  
- **Writing modified PDB files**  
- **Performing multiple sequence alignment (MSA)** using **MUSCLE**  
- **Downloading homologous structures** from the PDB database via sequence-based BLAST search  

These demos are ideal for users who are getting started with Bio3D and want to understand its core capabilities.

### `example/` — Application Examples

This folder contains two comprehensive examples demonstrating practical applications of Bio3D:

1. **Comparative Analysis of apo-CaM and holo-CaM**
   - Structural comparison of Calmodulin in its calcium-free (apo) and calcium-bound (holo) forms
   - Calculation and visualization of torsion angle differences
   - RMSD and RMSF analysis of different conformational states

2. **Multiple Sequence and Structural Alignment of Fluorescent Proteins**
   - Perform MSA on a large set of fluorescent proteins
   - Identify structurally conserved core regions
   - Visualize B-factors of individual structures
   - Compute and visualize structural RMSD, RMSF, and superposition

## Visualization Tools

- **PyMOL** and **ChimeraX** can be used to visualize structural data (PDB files)
- **JalView** is recommended for visualizing multiple sequence alignment (MSA) results

## Important Notes

- Bio3D’s multiple sequence alignment functionality **requires MUSCLE**
- **MUSCLE v5.0 is currently not supported** by Bio3D. Please use **MUSCLE v3** instead.

## Useful Links

- 📘 [Bio3D User Guide](http://thegrantlab.org/bio3d_v2/user-guide)  
- 📚 [Bio3D Tutorials](http://thegrantlab.org/bio3d_v2/tutorials)  
- 🐛 [Report Issues](https://bitbucket.org/Grantlab/bio3d/issues?status=new&status=open)  
