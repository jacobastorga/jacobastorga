# Jacob Astorga

**Mechanical Engineer & Computational Simulation SME**  
*Specializing in Structural FEA, Additive Manufacturing (DFAM), and AI Training & Benchmark Verification.*

---

## 🔬 About Me

I am a mechanical engineer with a strong cross-disciplinary foundation in **computational solid mechanics, computer science, and AI training / evaluation systems**. My technical background spans continuum mechanics, finite element analysis (FEA), polymer anisotropy, and automated simulation pipelines—coupled with software engineering, automated testing, and LLM alignment.

In the AI evaluation space, I bridge physical engineering principles with rigorous machine learning data curation and validation:
* **Engineering & Simulation SME:** Designing deterministic simulation-scored benchmarks, kinematic boundary conditions, and material derating models for mechanical design challenges.
* **Computer Science & AI Tooling:** Engineering automated test suites, web-grounding verification pipelines, multimodal processing utilities, and programmatic verifiers (Outcome Reward Models) that evaluate AI code and reasoning.

---

## 🛠️ Technical Toolkit

| Domain | Tools & Technologies |
| :--- | :--- |
| **Mechanical & Structural FEA** | CalculiX CrunchiX (`ccx`), Code_Aster, Linear Static, Eigenvalue Buckling, ASME V&V 20 GCI Convergence |
| **CAD & Parametric Geometry** | FreeCAD (PartDesign, OpenCASCADE B-Rep), PythonOCC, CadQuery, STEP AP214/AP242 |
| **Meshing & Discretization** | Gmsh (C3D10 quadratic tetrahedra, field-based curvature refinement), Netgen |
| **DFAM & Additive Manufacturing** | PrusaSlicer CLI, UltiMaker CuraEngine, FDM/FFF orthotropic derating, Trimesh, 2-manifold verification |
| **Computer Science & Automation** | Python, Java, Linux/POSIX Shell, Docker, Git CI/CD, Algorithms & Data Structures, Unit Testing (`pytest`, `JUnit`) |
| **AI Training & Evaluation** | SFT Dataset Curation, Automated Code Evaluation, Fact-Checking Pipelines, Multimodal Transforms (OpenCV, FFmpeg) |

---

## 🏗️ Mechanical Engineering & Computational Simulation Architectures

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

---

## 💻 Computer Science, AI Training & Evaluation Tooling

*(Separate software engineering & machine learning pipeline artifacts)*

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

> *"A simulation is only as reliable as its boundary condition formulation and mesh convergence proof. In automated engineering and AI evaluation, the goal is not merely finding a passing scalar number, but verifying that the governing physics, material anisotropy, and manufacturing constraints are fully respected."*

---

### 📫 Connect
* **GitHub:** [@jacobastorga](https://github.com/jacobastorga)
* **Focus Areas:** Mechanical SME, Structural FEA, Additive Manufacturing DFAM, AI Evaluation Benchmarking
