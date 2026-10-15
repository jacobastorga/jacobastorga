# Jacob Astorga

**Mechanical Engineer & Computational Simulation SME**  
*Specializing in Structural FEA, Additive Manufacturing (DFAM), and AI Training & Benchmark Verification for Engineering Reasoning.*

---

## 🔬 About Me

I am a mechanical engineer with a deep foundation in **computational solid mechanics, computer science, and AI training / evaluation workflows**. My technical focus centers on bridging physical continuum mechanics (FEA, non-linear stress states, polymer anisotropy, fatigue, and buckling) with automated software systems, reproducible simulation toolchains, and machine learning alignment.

In the AI space, I specialize in **domain-specific AI training, instruction-tuning data curation (SFT), and designing programmatic verification harnesses for RLHF/RLAIF**:
* **Computer Science & Automation:** Building modular, test-driven Python architectures, sandboxed headless simulation pipelines (FreeCAD, Gmsh, CalculiX, ParaView), and containerized evaluation environments.
* **AI Training & Ground-Truth Verification:** Formulating rigorous multi-constraint engineering prompts, engineering deterministic verifiers (Outcome Reward Models / ORMs) that validate physical ground truth, and red-teaming tool-using agents against reward hacking, unit-scaling exploits, and non-physical boundary cheats.

---

## 🛠️ Core Engineering, CS & AI Toolkit

| Domain | Tools & Technologies |
| :--- | :--- |
| **Mechanical & Structural FEA** | CalculiX CrunchiX (`ccx`), Code_Aster, Linear Static, Eigenvalue Buckling, ASME V&V 20 GCI Convergence |
| **CAD & Parametric Geometry** | FreeCAD (PartDesign, OpenCASCADE B-Rep), PythonOCC, CadQuery, STEP AP214/AP242 |
| **Meshing & Discretization** | Gmsh (C3D10 quadratic tetrahedra, field-based curvature refinement), Netgen |
| **DFAM & Additive Manufacturing** | PrusaSlicer CLI, UltiMaker CuraEngine, FDM/FFF orthotropic derating, Trimesh, 2-manifold verification |
| **Computer Science & Infrastructure** | Python (`numpy`, `scipy`, `trimesh`, `pytest`), Linux/POSIX Shell, Docker, Git CI/CD, Algorithms & Data Structures |
| **AI Training & Evaluation** | SFT Dataset Curation, RLHF Preference Rubrics, Process/Outcome Verifiers (PRM/ORM), Agent Red-Teaming |

---

## 🚀 Featured Engineering Projects & Architectures

### 1. [Open-Source Structural FEA & Automated Convergence Pipeline (`open-fea-mesh-optimizer`)](https://github.com/jacobastorga/open-fea-mesh-optimizer)
> **Stack:** Python, FreeCAD OpenCASCADE, Gmsh API, CalculiX (`ccx`), ParaView
* An automated computational pipeline that generates parametric B-Rep CAD geometry, builds conformal 10-node quadratic tetrahedral meshes (`C3D10`), executes implicit linear static & buckling solves in CalculiX, and automates mesh convergence verification using the ASME V&V 20 Grid Convergence Index (GCI).
* Eliminates shear locking, handles reentrant notch singularities via Saint-Venant extraction, and automates multi-objective mass-stiffness optimization.

### 2. [DFAM Geometry & Slicer Validation Engine (`dfam-printability-validator`)](https://github.com/jacobastorga/dfam-printability-validator)
> **Stack:** Python, Trimesh, PrusaSlicer CLI, Shapely, FDM Polymer Mechanics
* A headless additive manufacturing validation harness for structural FDM/FFF parts. Programmatically evaluates 2-manifold watertightness, Euler-Poincaré genus characteristics, minimum printable wall thresholds ($\ge 2.4\text{ mm}$), and critical overhang angles ($> 45^\circ$).
* Integrates an anisotropic material derating framework that adjusts allowable stresses based on print orientation (XY continuous raster vs. weak Z-axis interlayer cleavage) and viscoelastic creep thresholds.

### 3. [Autonomous Mechanical Agent Evaluation & Benchmark Harness (`mech-agent-eval-harness`)](https://github.com/jacobastorga/mech-agent-eval-harness)
> **Stack:** Python, Docker, CalculiX, FreeCAD API, Automated Verification Logic
* A benchmarking harness built to test and evaluate autonomous coding and engineering agents on multi-constraint mechanical design challenges.
* Contains deterministic check algorithms designed to detect AI agent shortcuts: full-face clamping cheats, non-physical kinematic rigid-body stiffening, unit-inconsistency glitches ($10^6$ MPa modulus errors), and paper-thin unprintable membrane geometries.
* Functions as a programmatic ground-truth verifier (Outcome Reward Model) for reinforcement learning (RL) training loops in engineering domains.

---

## 📐 Engineering Philosophy

> *"A simulation is only as reliable as its boundary condition formulation and mesh convergence proof. In automated engineering and AI evaluation, the goal is not merely finding a passing scalar number, but verifying that the governing physics, material anisotropy, and manufacturing constraints are fully respected."*

---

### 📫 Connect
* **GitHub:** [@jacobastorga](https://github.com/jacobastorga)
* **Focus Areas:** Mechanical SME, Structural FEA, Additive Manufacturing DFAM, AI Training & Benchmark Evaluation
