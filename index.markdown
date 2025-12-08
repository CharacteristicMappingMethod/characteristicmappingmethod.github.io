---
layout: homepage
---

<div style="text-align: center;">

<h1>CROKE</h1>

<h2>-Characteristic mapping for Kinetic Equations-</h2>
<h3> from theory to simulations and Reduced Order methods </h3>

</div> 

In this project, we introduce the characteristic mapping method to address the complexity of high-
dimensional kinetic equations, such as those involving ion-electron interactions in plasma fusion, by integrating mathematical modeling with high-performance computing. This semi-Lagrangian method achieves
exponential resolution in linear time, revealing ﬁne-scale details of the solutions and providing insights into
the filamentation structure of plasmas. By employing reduced-order models, we significantly lower the
numerical complexity of the computations. Our approach, which combines dimensionality reduction of
sub-maps with refinement through map compositions via the solution operator, is innovative and paves the
way for efficient evaluation of high-dimensional distribution functions across extended time intervals and
multi-scale spatial domains. This project is designed to test the potential to enhance existing semi-Lagrangian
techniques and advance our understanding of intricate local thermodynamic non-equilibrium phenomena in
plasmas, with applications in magnetically confined fusion.

## Team:

**LAGA, UMR 7030, Université Paris 13**
<br>
Olivier Lafitte (PI and coordinator)

**CEA - IRFM, Cadarache**
<br>
Kevin Obrejan and Philipp Krah

**I2M, UMR 7373, Aix-Marseille Université**
<br>
Kai Schneider

**McGill University, Montreal**
<br>
Jean-Christophe Nave 


## Positions Available:

### Master projects:

We are looking for talented and motivated master students in computational physics, applied mathematics or data-science.
The proposed Master’s projects can be carried out either as a 6-month internship or as part of a Master’s thesis.
These projects are funded, and we only accept Master’s students who are interested in pursuing a PhD afterwards.
The projects can take place within one of three teams: CEA, LAGA–Paris, or I2M (Aix-Marseille University).

- Evolving flow maps using neural-semi Lagrangian method: [Proposal](https://characteristicmappingmethod.github.io/assets/projects/neural_SL_CMM.pdf)
- Data-assimilation for plasma simulations: [Proposal](https://characteristicmappingmethod.github.io/assets/projects/adjoint_plasma.pdf)
- Learning neural operators gfor drift kinetic equations: [Proposal]

### PhD + PostDoc Positions

Two positions are available within our research consortium. Candidates will be integrated into one of our partner teams.

---

#### **Position 1: Advanced Model Reduction for Kinetic Plasmas**

##### Project Description
This project focuses on pioneering data-driven and mathematical techniques to construct compact, efficient models of complex plasma systems. The primary objective is to overcome the "curse of dimensionality" by developing accurate low-dimensional representations of high-dimensional flow maps, leveraging their inherent compositional (semi-group) structure. The research will explore hybrid methodologies combining Neural Implicit Representations and Dynamic Low-Rank Approximations.

##### Candidate Profile
We seek a candidate with a background in **Applied Mathematics, Data Science, or Computational Physics**.

- **Required:**
  - Proven knowledge in machine learning and/or model order reduction
  - Strong programming skills in C++ and PyTorch

- **Advantageous:**
  - Familiarity with partial differential equations

##### Keywords
Model Order Reduction, Neural Implicit Flow Maps, Low-Rank Approximation, Scientific Machine Learning, Plasma Physics

---

#### **Position 2: High-Performance Plasma Simulation for Fusion**

##### Project Description
This project aims to generalize the Characteristic Mapping Method (CMM) for realistic simulations of magnetically confined plasmas in fusion devices (Vlasov-Maxwell and Gyrokinetic). The work will involve the implementation and testing of realistic boundary conditions, the generalization of source term handling for collisions and heating, and the development of robust numerical schemes. Given the high-dimensional nature of the simulations, the implementation will be designed for High-Performance Computing (HPC) environments from the ground up.

##### Candidate Profile
We seek a candidate with a background in **Applied Mathematics, Computational Physics, or Scientific Computing/Informatics**.

- **Required:**
  - Solid foundation in numerical methods for partial differential equations
  - Proficiency in C++ and HPC programming (e.g., MPI, CUDA, job schedulers, Git)

- **Advantageous:**
  - Basic knowledge of plasma physics

##### Keywords
Vlasov-Maxwell Equations, Gyrokinetics, High-Performance Computing (HPC), Characteristic Mapping Method, Plasma-Fusion

---

*Both positions offer competitive funding, access to state-of-the-art computing facilities, and collaboration opportunities within an international research network.*

For interested candidates please contact:
[philipp.krah@cea.fr](mailto:philipp.krah@cea.fr) 

---

[Visit the old Adaptive-CMM project →]({{ '/adaptive-cmm/' | relative_url }})
