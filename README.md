# Development of a Design-Through-Analysis Isogeometric Module in FEAST: Towards Structural Analysis and Optimization

## Deadline
The project is supposed to start on: **August 1st week**.
Internal submission deadline: **September 2024**.
The project submission deadline: **January 2025**.
## Description
This project proposal aims to develop a design-through-analysis isogeometric module in FEAST for structural analysis and optimization. The work will focus on integrating Iso-Geometric Analysis (IGA) into ISRO's structural analysis software, FEAST, to improve accuracy, efficiency, and ease of use in structural engineering tasks.

## Background
- **Finite Element Method (FEM):**
  - Industry standard in Computer-Aided Engineering (CAE) for decades.
  - Drawbacks: Effort-intensive CAD to FEM model conversion, limited C0 continuity, high computational effort for complex geometries.
- **Iso-Geometric Analysis (IGA):**
  - Extends and generalizes classical FEM using CAD-based spline polynomials (NURBS, T-splines, PHT-splines).
  - Benefits: Reduced design-analysis communication time, exact geometry modeling, computational efficiency.
  - Effective for plate/shell structures, vibration analysis, nonlinear contact mechanics, and structural optimization.
## Project Objectives and Timelines
### Major Objectives

1. **GUI-Based Design-Through-Analysis Package for Isogeometric Analysis (IGA)**
	- Develop a standalone software package to carry out IGA using single-patch and multi-patch NURBS.
	- Enable the creation of geometries using NURBS and import NURBS data from other industry-standard CAD packages.
	- Provide provisions for applying various boundary conditions.
	- Implement isogeometric meshing of the analysis geometry.

2. **Static Analysis Module Using IGA**
	- Develop a GUI package to perform static analysis of 2D and 3D structural geometries.
	- Base the material model on linear-elastic behavior.
	- Use plane stress and plane strain idealization.
	- Add multi-patch conforming capabilities.

3. **Eigenvalue Analysis Module Using IGA**
	- Develop an eigenvalue analysis module to perform dynamic analysis of 2D geometries.
	- Analyze the free vibration response of linear-elastic materials.

4. **Validation of Developed Computer Codes**
	- Generate test modules along with the codes for validation.
	- Validate against a few standard benchmark problems.

4. **Post-Processor for Visualizing IGA Results**
	- Develop a module to project IGA results onto NURBS mesh for visualization.
	- Create a module to display contour plots based on the stress resultants and other field variables.

## Deliverables
- GUI module developed (static analysis + eigenvalue analysis)
- Documentation of code and mathematical formulation

### Timeline - 
- The project is divided into 5 Activities and corresponding sub activities.
- Project completion is expected in 12 months.


![](attachments/Pasted%20image%2020240611185447.png)





