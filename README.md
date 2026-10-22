# Jacob Astorga

**Computational Scientist & AI Evaluation Specialist**  
*Specializing in Computational Mathematics, Continuum Mechanics, Scientific Simulation & Frontier Model Benchmark Task Authoring.*

---

## 🔬 About Me

I am a computational scientist and mechanical engineer with an interdisciplinary foundation bridging **computational mathematics, continuum physics, computer science, and frontier AI evaluation systems**. My technical background spans continuum mechanics, Navier-Stokes fluid dynamics, numerical ODE/PDE solvers, and automated simulation pipelines—coupled with software engineering, deterministic test harnesses, and LLM alignment.

In the AI evaluation and benchmark task authoring space, I bridge physical first-principles with programmatic mathematical verification:
* **Scientific Researcher & Benchmark Task Author:** Formulating research-grade computational physics and applied mathematics evaluation tasks. Authoring closed-form analytical proofs, programming deterministic Python reference solutions (`numpy`, `scipy.integrate`, `scipy.sparse`), and designing automated `pytest` verification harnesses enforcing boundary condition adherence and energy conservation balances.
* **Computer Science & AI Tooling:** Engineering automated test suites, web-grounding verification pipelines, multimodal processing utilities, and programmatic verifiers (Outcome Reward Models) that evaluate AI code and reasoning traces.

---

## 🛠️ Technical Toolkit

| Domain | Tools & Technologies |
| :--- | :--- |
| **Computational Mathematics & Solvers** | `scipy.integrate` (`solve_bvp`, `solve_ivp`), `scipy.sparse`, `scipy.optimize`, Runge-Kutta & Stiff Solvers (Radau, BDF), Crank-Nicolson, Finite Difference Method (FDM), Finite Element Method (FEM), CFL stability condition, matrix condition numbers, Taylor series convergence |
| **Continuum Mechanics & Structural FEA** | CalculiX CrunchiX (`ccx`), Gmsh API, Linear/Nonlinear Elasticity, Plasticity & Hardening, Von Mises & Tresca Yield, Euler-Bernoulli/Timoshenko Beam Theory, Fracture Mechanics, ASME V&V 20 GCI Convergence |
| **Fluid Dynamics & Transport PDEs** | Navier-Stokes equations, 2D Transient Advection-Diffusion-Reaction, Poiseuille/Couette Flows, Boundary Layer Equations, OpenFOAM, Vortex Dynamics |
| **CAD & Parametric Geometry** | FreeCAD (PartDesign, OpenCASCADE B-Rep), PythonOCC, CadQuery, STEP AP214/AP242 |
| **Computer Science & Automation** | Python, C++, Java, Linux/POSIX Shell, Docker, Git CI/CD, Algorithms & Data Structures, Unit Testing (`pytest`, `JUnit`) |
| **AI Benchmark Authoring & Evaluation** | Frontier Model Evaluation, Multi-step Chain-of-Thought (CoT) Verification, Gold-Standard Reference Solutions, Step-by-Step Mathematical Derivation Auditing, Outcome Reward Modeling |

---

## 🏛️ Computational Science & AI Benchmark Architectures

### 1. [Computational Physics & Mathematics AI Benchmarks (`computational-physics-benchmarks`)](https://github.com/jacobastorga/computational-physics-benchmarks)
> **Stack:** Python, NumPy, SciPy (`solve_bvp`, `sparse.linalg`), SymPy, PyTest
* A research-grade computational evaluation suite designed to benchmark frontier foundation models on complex physical and mathematical reasoning tasks.
* Features end-to-end benchmark tasks with parameterized subproblems, ground-truth reference solvers, and automated PyTest verification harnesses:
  * **Fluid Dynamics & Transport:** 2D transient advection-diffusion in channel flow with parabolic Poiseuille profile, Crank-Nicolson stepping, and net thermal energy conservation audits.
  * **Continuum Mechanics & Elasticity:** 2D elastoplastic stress concentration around a cutout under Von Mises yield with linear isotropic hardening and boundary force equilibrium assertions.
  * **Nonlinear Mechanics & ODEs:** Post-buckling bifurcation of an imperfect column solved via two-point boundary value collocation (`scipy.integrate.solve_bvp`) with pitchfork branch convergence verification.

### 2. [Open-Source Structural FEA & Automated Convergence Pipeline (`open-fea-mesh-optimizer`)](https://github.com/jacobastorga/open-fea-mesh-optimizer)
> **Stack:** Python, FreeCAD OpenCASCADE, Gmsh API, CalculiX (`ccx`), ParaView
* An automated computational pipeline that generates parametric B-Rep CAD geometry, builds conformal 10-node quadratic tetrahedral meshes (`C3D10`), executes implicit linear static & buckling solves in CalculiX, and automates mesh convergence verification using the ASME V&V 20 Grid Convergence Index (GCI).
* Eliminates shear locking, handles reentrant notch singularities via Saint-Venant extraction, and automates multi-objective mass-stiffness optimization.

### 3. [Autonomous Mechanical Agent Evaluation & Benchmark Harness (`mech-agent-eval-harness`)](https://github.com/jacobastorga/mech-agent-eval-harness)
> **Stack:** Python, Docker, CalculiX, FreeCAD API, Automated Verification Logic
* A benchmarking harness built to test and evaluate autonomous coding and engineering agents on multi-constraint mechanical design challenges.
* Contains deterministic check algorithms designed to detect AI agent shortcuts: full-face clamping cheats, non-physical kinematic rigid-body stiffening, unit-inconsistency glitches ($10^6$ MPa modulus errors), and paper-thin unprintable membrane geometries.

### 4. [DFAM Geometry & Slicer Validation Engine (`dfam-printability-validator`)](https://github.com/jacobastorga/dfam-printability-validator)
> **Stack:** Python, Trimesh, PrusaSlicer CLI, Shapely, FDM Polymer Mechanics
* A headless additive manufacturing validation harness for structural FDM/FFF parts. Programmatically evaluates 2-manifold watertightness, Euler-Poincaré genus characteristics, minimum printable wall thresholds ($\ge 2.4\text{ mm}$), and critical overhang angles ($> 45^\circ$).
* Integrates an anisotropic material derating framework that adjusts allowable stresses based on print orientation (XY continuous raster vs. weak Z-axis interlayer cleavage) and viscoelastic creep thresholds.

---

## 💻 Computer Science, AI Training & Evaluation Tooling

### 1. [LLM Code & Reasoning Benchmark Suite (`llm-code-benchmark-suite`)](https://github.com/jacobastorga/llm-code-benchmark-suite)
> **Stack:** Python, Java, Pytest, JUnit, Subprocess Sandboxing
* Automated test harnesses designed for grading and evaluating AI-generated code.
* Assesses syntax validity, boundary edge cases, algorithmic time/space complexity, and sandboxed runtime efficiency to generate objective ground-truth pass/fail signals for model evaluation.

### 2. [Web Research & Citation Fact-Checker (`web-citation-fact-checker`)](https://github.com/jacobastorga/web-citation-fact-checker)
> **Stack:** Python, BeautifulSoup4, Requests, Regex Parsing
* Automated verification pipeline that cross-references AI-generated claims and URLs against live web sources.
* Extracts cited references, detects broken links / 404s, parses source HTML content, and flags hallucinated or misleading citations in technical research outputs.

### 3. [Multimodal Data Augmentation Pipeline (`multimodal-data-augmentation`)](https://github.com/jacobastorga/multimodal-data-augmentation)
> **Stack:** Python, OpenCV, FFmpeg, NumPy
* Batch processing suite for multimodal dataset curation and preprocessing.
* Automates spatial geometric image transforms, high-throughput video frame extraction, and multimodal audio-visual alignment pipelines for AI training data pipelines.

---

## 📐 Engineering & Systems Philosophy

> *"A simulation is only as reliable as its boundary condition formulation and mesh convergence proof. In computational mathematics and AI benchmark evaluation, the objective is not merely matching an empirical scalar, but verifying that the underlying governing differential equations, boundary fluxes, and conservation laws are rigorously upheld."*

---

### 📫 Connect
* **LinkedIn:** [linkedin.com/in/jacob-astorga-895405416](https://www.linkedin.com/in/jacob-astorga-895405416/)
* **GitHub:** [@jacobastorga](https://github.com/jacobastorga)
* **Focus Areas:** Computational Mathematics, Continuum Mechanics, Fluid Dynamics, Scientific Computing, AI Benchmark Task Authoring
