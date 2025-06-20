---
title: Finite Element Mesh
---

# Module 8: Finite Element Mesh
**Duration:** 3 hours  
**Instructor:** Amanda Taylor

## Learning Objectives

By the end of this module, participants will be able to:
- Understand finite element mesh concepts for HGS
- Compare open-source and commercial meshing tools
- Work with spline controls and polygon properties
- Optimize mesh quality and element sizes
- Generate and export meshes in appropriate file formats

## Module Content

### 8.1 What is a FEM for HGS?
- Finite element method fundamentals
- Mesh requirements for integrated surface-subsurface modeling
- Element types and characteristics
- Mesh density considerations

### 8.2 Open vs. Closed Source Meshing Software
- **GMSH:** Open-source mesh generator
  - Advantages and capabilities
  - Integration with HGS workflows
  - Community support and documentation
- **Algomesh:** Commercial mesh generator
  - Advanced features and automation
  - Cost-benefit considerations
  - Proprietary limitations

### 8.3 Spline Controls
- Spline definition and applications
- Boundary representation
- Curve smoothing and refinement
- Geometric constraints

### 8.4 Polygon Properties
- Material zone definition
- Mesh density assignment
- Boundary condition specification
- Layered geometry handling

### 8.5 Edge Lengths, Optimization and Mesh Quality
- Element size gradation
- Aspect ratio considerations
- Skewness and quality metrics
- Mesh refinement strategies
- Convergence testing

### 8.6 File Formats
- HGS mesh file formats
- Import/export procedures
- Format conversion tools
- Quality assurance workflows

## Practical Exercises

- Creating a simple 2D mesh using GMSH
- Defining material zones and boundaries
- Mesh quality assessment and optimization
- Exporting meshes for HGS

## Software Tools

- GMSH (open source)
- ParaView for mesh visualization
- HGS preprocessing tools
- Python mesh processing libraries

## Key Takeaways

- Mesh quality directly impacts model accuracy and stability
- Open-source tools provide flexibility and cost advantages
- Proper mesh design requires balancing accuracy and computational efficiency
- Iterative refinement is often necessary for complex geometries
