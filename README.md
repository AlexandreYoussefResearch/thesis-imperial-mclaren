# Development of Mesh Deformation Methods for External Aerodynamics Simulations  
**Imperial College London – MSc Thesis (in collaboration with McLaren Racing)**

This repository contains the public version of my MSc thesis (non-confidential version only), conducted within the **CFD R&D team at McLaren Racing** as part of the Aeronautics programme at Imperial College London.

The project investigates the development and evaluation of **PDE-based mesh deformation methods** to support accurate simulation of **external aerodynamics** under large, random vehicle displacements. Classical techniques such as **Laplace**, **Linear Elasticity**, and **Biharmonic** equations are compared in terms of mesh quality preservation, numerical stability, and implementation robustness.

In addition to these methods, the work explores the integration of **point set registration techniques** - commonly used in **computer vision** to align two sets of spatial points (e.g., shapes, objects, boundaries). These techniques aim to compute non-rigid transformations that best match one point set to another. In the context of mesh deformation, they provide an elegant way to infer smooth and realistic displacement fields when vehicle geometries undergo irregular or large motion.

## Contents

- Benchmark and comparison of mesh deformation solvers
- Mesh quality metrics and Jacobian preservation
- Randomized track motion model for realistic vehicle displacement
- Application of **non-rigid registration** to define boundary-conforming displacements
- Mathematical tools bridging numerical simulation and geometric processing

> This repository includes only the public version of the report. All implementation details remain confidential.

---

## Contact

For any inquiries:  
**alexandre.youssef.pro@gmail.com**
