# Jacob Astorga

**Mechanical Engineer & Computational Simulation SME**  
*Specializing in Structural FEA, Design for Additive Manufacturing (DFAM), and Engineering Benchmark Evaluation for Autonomous AI Agents.*

---

## 🔬 About Me

I am a mechanical engineer with a focus on **computational structural mechanics, open-source FEA/CAD automation, and rigorous evaluation of engineering AI systems**. My work bridges fundamental mechanical principles (continuum mechanics, anisotropic material derating, fatigue, buckling) with automated software toolchains (FreeCAD, Gmsh, CalculiX, ParaView, and headless slicers).

In AI evaluation and technical benchmarking, I design deterministic simulation-scored engineering challenges, formulate robust kinematic boundary conditions, and engineer automated checking harnesses that catch mathematical exploits, non-physical boundary cheats, and reward hacking in tool-using AI models.

---

## 🛠️ Core Engineering & Computational Toolkit

| Domain | Tools & Technologies |
| :--- | :--- |
| **CAD & Parametric Geometry** | FreeCAD (PartDesign, OpenCASCADE B-Rep), PythonOCC, STEP AP214/AP242, CadQuery |
| **Meshing & Discretization** | Gmsh (C3D10 quadratic tetrahedra, field-based boundary refinement), Netgen |
| **Finite Element Analysis (FEA)** | CalculiX CrunchiX (`ccx`), Code_Aster, Linear Static, Eigenvalue Buckling, GCI Convergence |
| **DFAM & Additive Manufacturing** | PrusaSlicer CLI, UltiMaker CuraEngine, FDM/FFF orthotropic derating, Trimesh, 2-manifold verification |
| **Post-Processing & Automation** | ParaView, Python (`numpy`, `scipy`, `trimesh`, `matplotlib`), Bash/PowerShell CI harnesses |
| **Evaluation & Benchmarking** | Boundary condition verification, stress singularity extraction, kinematic coupling audits |

---

## 🚀 Featured Engineering Projects & Architectures

### 1. [Open-Source Structural FEA & Automated Convergence Pipeline (`open-fea-mesh-optimizer`)](https://github.com/jacobastorga/open-fea-mesh-optimizer)
> **Stack:** Python, FreeCAD OpenCASCADE, Gmsh API, CalculiX (`ccx`), ParaView
* An automated end-to-end computational pipeline that generates parametric B-Rep CAD geometry, builds conformal 10-node quadratic tetrahedral meshes (`C3D10`), executes implicit linear static & buckling solves in CalculiX, and automates mesh convergence verification using the ASME V&V 20 Grid Convergence Index (GCI).
* Eliminates shear locking, handles reentrant notch singularities via Saint-Venant extraction, and automates multi-objective mass-stiffness optimization.

### 2. [DFAM Geometry & Slicer Validation Engine (`dfam-printability-validator`)](https://github.com/jacobastorga/dfam-printability-validator)
> **Stack:** Python, Trimesh, PrusaSlicer CLI, Shapely, FDM Polymer Mechanics
* A headless additive manufacturing validation harness for structural FDM/FFF parts. Programmatically evaluates 2-manifold watertightness, Euler-Poincaré genus characteristics, minimum printable wall thresholds ($\ge 2.4\text{ mm}$), and critical overhang angles ($> 45^\circ$).
* Integrates an anisotropic material derating framework that adjusts allowable stresses based on print orientation (XY continuous raster vs. weak Z-axis interlayer cleavage) and viscoelastic creep thresholds.

### 3. [Autonomous Mechanical Agent Evaluation & Benchmark Harness (`mech-agent-eval-harness`)](https://github.com/jacobastorga/mech-agent-eval-harness)
> **Stack:** Python, Docker, CalculiX, FreeCAD API, Automated Verification Logic
* A benchmarking harness built to test and evaluate autonomous coding and engineering agents on multi-constraint mechanical design challenges.
* Contains deterministic check algorithms designed to detect AI agent shortcuts: full-face clamping cheats, non-physical kinematic rigid-body stiffening, unit-inconsistency glitches ($10^6$ MPa modulus errors), and paper-thin unprintable membrane geometries.

---

## 📐 Engineering Philosophy

> *"A simulation is only as reliable as its boundary condition formulation and mesh convergence proof. In automated engineering and AI evaluation, the goal is not merely finding a passing scalar number, but verifying that the governing physics, material anisotropy, and manufacturing constraints are fully respected."*

---

### 📫 Connect
* **GitHub:** [@jacobastorga](https://github.com/jacobastorga)
* **Focus Areas:** Mechanical SME, Structural FEA, Additive Manufacturing DFAM, AI Evaluation Benchmarking
