# Jacob Astorga

**Systems Engineer, Software Developer & Computational AI Specialist**  
*Bridging ABET-Accredited Mechanical Engineering, CAD/FEA Simulation Pipelines, Enterprise Software Development & Frontier AI Model Alignment.*

---

## 🔬 About Me

I am a multi-disciplinary Systems Engineer and Software Developer with an interdisciplinary foundation bridging an **ABET-accredited BS in Mechanical Engineering (The University of Texas at El Paso)** and a **Bachelor's Degree in Software Development / Computer Science (Dallas College)**.

My background unites classical mechanical engineering principles—continuum mechanics, finite element analysis (FEA), 3D CAD modeling, ASME Y14.5 GD&T tolerance analysis, and fluid dynamics—with enterprise software engineering (Java, Python, C++, REST APIs, CI/CD), automated test harnesses (PyTest, JUnit 5), and frontier AI model alignment (RLHF / DPO / Tool-Calling).

### Core Focus Areas:
* **Mechanical & Computational Engineering:** Parametric CAD modeling (SolidWorks, PTC Creo, FreeCAD), ASME Y14.5 GD&T tolerance stackup (worst-case & RSS), conformal tetrahedral meshing (Gmsh, CalculiX ccx), and deterministic PDE/ODE solvers for thermo-mechanical conduction and stress analysis.
* **AI Training & RLHF/DPO Alignment:** Designing automated AST pipelines to audit intermediate Chain-of-Thought derivations, eliminate mathematical hallucinations, enforce physical conservation laws, and curate high-signal (chosen, rejected) preference pairs.
* **Agentic Systems & Tool-Use Evaluation:** Benchmarking autonomous engineering and coding agents on multi-step tool execution, JSON schema compliance, parameter hallucination detection, and causal DAG dependency graphs.
* **Enterprise Software Engineering & Automated QA:** Asynchronous workflow engines (AsyncIO, Kahn's topological sort), declarative API contract fuzzers, mock test fixtures, boundary regression suites, and CI/CD pipelines.
* **Multilingual & Cross-Lingual NLP:** English-to-Swahili (Kiswahili) semantic translation fidelity, Bantu noun-class grammatical concord verification, and low-resource reasoning alignment.

---

## 🛠️ Technical Toolkit

| Domain | Tools & Technologies |
| :--- | :--- |
| **Mechanical Engineering & CAD Design** | SolidWorks, PTC Creo, FreeCAD / OpenCASCADE, AutoCAD, GD&T (ASME Y14.5), Tolerance Stackup (Worst-Case & RSS), DFM/DFA |
| **FEA, Physics Simulation & Continuum Mechanics** | CalculiX CrunchiX (ccx), Gmsh API, Finite Element Analysis (FEA), Finite Difference Method (FDM), Fourier Heat Conduction, Navier-Stokes Fluid Dynamics |
| **Enterprise Software Engineering** | Python (AsyncIO, FastAPI), Java (Spring Boot), C++, REST APIs, OpenAPI, JSON Schema, SQL (PostgreSQL), Docker, Linux, CI/CD |
| **Automated Software Testing & QA** | PyTest automated test harnesses, JUnit 5, Test-Driven Development (TDD), Mock Fixtures, AST Cyclomatic Complexity |
| **AI Training & Alignment (RLHF / DPO)** | DPO Pairwise Preference Curation, CoT Derivation Auditing, Hallucination Detection, Bradley-Terry Scoring, AST Complexity Scoring |
| **Agentic Systems & Function Calling** | JSON Schema Parameter Validation, Isolated Sandbox Execution, Causal DAG Dependency Graphs, Tool Hallucination Auditing |
| **Multimodal QA & Cross-Lingual NLP** | CVAT 1.1 / Labelbox v2 Schema Export, SSIM / PSNR / Sobel Edge Analysis, Swahili (Kiswahili) Bilingual Evaluation & Concord Rules |

---

## 💻 Featured Open-Source Repositories & Engineering Portfolio

### 1. [Thermo-Mechanical FEA Conduction & Stress Solver (`thermo-mechanical-fea-solver`)](https://github.com/jacobastorga/thermo-mechanical-fea-solver)
> **Stack:** Python, NumPy, SciPy, Finite Difference Method (FDM), Plane Strain Elasticity, PyTest  
* 2D steady-state finite difference thermal conduction solver with temperature-dependent conductivity $k(T)$, Robin boundary convection, and thermo-elastic plane strain stress evaluation for semiconductor microelectronics packaging and heat sink dissipation.

### 2. [ASME Y14.5 GD&T Tolerance Stackup Analyzer (`asme-gdt-tolerance-analyzer`)](https://github.com/jacobastorga/asme-gdt-tolerance-analyzer)
> **Stack:** Python, NumPy, ASME Y14.5-2018, Monte Carlo Simulation, PyTest  
* High-precision parametric 1D and 2D tolerance stackup calculation engine evaluating worst-case (arithmetic) loop closure, Root-Sum-Square (RSS) statistical variance, and 100,000-sample Monte Carlo normal/uniform yield distributions for mechanical assemblies.

### 3. [Cross-Lingual Swahili NLP Evaluator (`cross-lingual-swahili-nlp-evaluator`)](https://github.com/jacobastorga/cross-lingual-swahili-nlp-evaluator)
> **Stack:** Python, NLP Tokenization, Bantu Grammar Concord Rules, Multilingual Evaluation, PyTest  
* Cross-lingual evaluation harness for benchmarking English-to-Swahili foundation model translations, semantic alignment, and low-resource reasoning fidelity. Validates noun-class grammatical concords (Classes 1–10) and flags unlocalized technical borrowings.

### 4. [Synthetic Image Artifact Detector & Multimodal QA (`synthetic-image-artifact-detector`)](https://github.com/jacobastorga/synthetic-image-artifact-detector)
> **Stack:** Python, NumPy, Sobel Gradients, SSIM / PSNR, CVAT 1.1 JSON, Labelbox v2 NDJSON  
* Computer vision quality assurance pipeline and defect auditing harness designed for multimodal AI evaluation, synthetic-vs-original image comparison, and training data annotation. Converts detected anomalies into standardized CVAT and Labelbox polygon segmentation schemas.

### 5. [Agentic Tool Call Evaluator (`agentic-tool-call-evaluator`)](https://github.com/jacobastorga/agentic-tool-call-evaluator)
> **Stack:** Python, JSON Schema, PyTest, Pydantic, Abstract Execution Sandboxes  
* Benchmarking framework for evaluating autonomous coding agents and LLMs on multi-step tool calling, JSON schema compliance, and causal DAG dependency ordering. Features strict parameter hallucination detection and stateful in-memory execution sandboxing.

### 6. [RLHF Reasoning Alignment & Verification Suite (`rlhf-reasoning-alignment`)](https://github.com/jacobastorga/rlhf-reasoning-alignment)
> **Stack:** Python, NumPy, PyTest, AST Step Tokenization, DPO / RLHF Bradley-Terry Scoring  
* Step-level factuality auditing and pairwise DPO preference dataset curation harness for frontier mathematical and scientific reasoning models. Audits intermediate Chain-of-Thought steps for numerical tolerance bounds ($|y_{\text{pred}} - y_{\text{ref}}| \le \epsilon$) and detects spurious heuristic leaps.

### 7. [Async Task Orchestrator & DAG Workflow Engine (`async-task-orchestrator`)](https://github.com/jacobastorga/async-task-orchestrator)
> **Stack:** Python, AsyncIO, Kahn's Topological Sorting, SQLite, PyTest, Concurrency Semaphores  
* High-performance asynchronous DAG task execution engine with automated cycle detection (3-color DFS), non-blocking worker concurrency control, exponential backoff retries, and embedded SQLite execution state persistence.

### 8. [REST API Schema Guard & Contract Fuzzer (`rest-api-schema-guard`)](https://github.com/jacobastorga/rest-api-schema-guard)
> **Stack:** Python, JSON Schema, OpenAPI Contracts, Property Validation, Adversarial Fuzzing, PyTest  
* Declarative REST API contract testing and JSON Schema validation framework enforcing strict type bounds and property constraints while running automated boundary fuzzing to ensure 100% negative test case rejection.

### 9. [DPO Code Preference Pipeline (`dpo-code-preference-pipeline`)](https://github.com/jacobastorga/dpo-code-preference-pipeline)
> **Stack:** Python, AST (Abstract Syntax Trees), PyTest, JSONL Dataset Serialization  
* Automated pipeline for curating, auditing, scoring, and formatting pairwise preference datasets `(chosen, rejected)` for Direct Preference Optimization (DPO) and RLHF. Features AST cyclomatic complexity analysis and anti-reward gaming heuristics.

### 10. [Computational Physics & Mathematics AI Benchmarks (`computational-physics-benchmarks`)](https://github.com/jacobastorga/computational-physics-benchmarks)
> **Stack:** Python, NumPy, SciPy (`solve_bvp`, `sparse.linalg`), SymPy, PyTest  
* Research-grade computational evaluation suite designed to benchmark frontier foundation models on complex physical and mathematical reasoning tasks (2D Advection-Diffusion, Elastoplasticity, Nonlinear Beam Buckling).

---

## 📐 Engineering & Systems Philosophy

> *"In automated software engineering and AI evaluation, the objective is not merely matching an empirical text output, but verifying that the underlying AST complexity, tool-calling schemas, and causal execution graphs are rigorously sound and free from reward hacking."*

---

### 📫 Connect
* **LinkedIn:** [linkedin.com/in/jacob-astorga-895405416](https://www.linkedin.com/in/jacob-astorga-895405416/)
* **GitHub:** [@jacobastorga](https://github.com/jacobastorga)
* **Focus Areas:** AI Training & Alignment (RLHF / DPO), Agentic Tool Calling, Code Evaluation Benchmarks, Computational Modeling
