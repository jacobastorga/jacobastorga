# Jacob Astorga

**Computational Scientist, Software Engineer & AI Evaluation Specialist**  
*Specializing in AI Model Training Pipelines, RLHF/DPO Preference Curation, Agentic Tool Evaluation & Computational Benchmarks.*

---

## 🔬 About Me

I am a software engineer and computational scientist with an interdisciplinary foundation bridging **software development, frontier AI training pipelines, and computational modeling**. My work centers on designing automated evaluation harnesses, curating high-signal preference datasets for Direct Preference Optimization (DPO), and stress-testing autonomous agent tool calling.

In the AI training and evaluation space:
* **RLHF & DPO Preference Engineering:** Designing automated AST pipelines to score code completions, detect subtle model reward-hacking tricks (empty pass stubs, broad exception swallowing), and generate clean `(chosen, rejected)` training pairs.
* **Agentic Tool-Use Evaluation:** Benchmarking autonomous coding agents on multi-step function calling, JSON schema compliance, argument hallucination detection, and causal DAG dependency ordering.
* **Scientific & Code Benchmarks:** Formulating deterministic test suites, unit testing harnesses (`pytest`), and mathematical proofs enforcing boundary conditions and ground-truth validation.

---

## 🛠️ Technical Toolkit

| Domain | Tools & Technologies |
| :--- | :--- |
| **AI Training & Alignment (RLHF / DPO)** | DPO Preference Dataset Curation, SFT Golden Data Authoring, Reward Model Scaffolding, AST Complexity Scoring, Anti-Reward Hacking Filters |
| **Agentic Systems & Function Calling** | JSON Schema Validation, Mock Sandboxed Execution Environments, Dependency DAG Analysis, Parameter Hallucination Auditing |
| **Computer Science & Software Engineering** | Python, C++, Java, Linux/POSIX Shell, Docker, Git CI/CD, Algorithms & Data Structures, Unit Testing (`pytest`, `JUnit`) |
| **Computational Mathematics & Solvers** | `scipy.integrate` (`solve_bvp`, `solve_ivp`), `scipy.sparse`, `scipy.optimize`, Runge-Kutta & Stiff Solvers (Radau, BDF), Crank-Nicolson, Finite Difference Method (FDM) |
| **Continuum Mechanics & Structural FEA** | CalculiX CrunchiX (`ccx`), Gmsh API, Linear/Nonlinear Elasticity, Plasticity & Hardening, Von Mises & Tresca Yield |

---

## 💻 Computer Science & AI Training Tooling

### 1. [Agentic Tool Call Evaluator (`agentic-tool-call-evaluator`)](https://github.com/jacobastorga/agentic-tool-call-evaluator)
> **Stack:** Python, JSON Schema, Pytest, Pydantic, Abstract Execution Sandboxes
* A production-grade evaluation harness and benchmarking framework for assessing autonomous coding agents and LLMs on **multi-step tool calling, JSON schema compliance, and causal dependency ordering**.
* Features strict parameter hallucination detection (flagging parameters not defined in tool specifications), an isolated in-memory stateful execution sandbox, and a causal DAG analyzer catching out-of-order execution anti-patterns.

### 2. [DPO Code Preference Pipeline (`dpo-code-preference-pipeline`)](https://github.com/jacobastorga/dpo-code-preference-pipeline)
> **Stack:** Python, AST (Abstract Syntax Trees), Pytest, JSONL Dataset Serialization
* Automated engineering pipeline for curating, auditing, scoring, and formatting pairwise preference datasets `(chosen, rejected)` for **Direct Preference Optimization (DPO)** and **RLHF**.
* Features AST-based cyclomatic complexity auditing, anti-reward gaming heuristics (detecting empty `pass` stubs, ellipsis placeholders, and unhandled exception swallowing), and an isolated test execution sandbox.

### 3. [LLM Code & Reasoning Benchmark Suite (`llm-code-benchmark-suite`)](https://github.com/jacobastorga/llm-code-benchmark-suite)
> **Stack:** Python, Java, Pytest, JUnit, Subprocess Sandboxing
* Automated test harnesses designed for grading and evaluating AI-generated code.
* Assesses syntax validity, boundary edge cases, algorithmic time/space complexity, and sandboxed runtime efficiency to generate objective ground-truth pass/fail signals for model evaluation.

### 4. [Web Research & Citation Fact-Checker (`web-citation-fact-checker`)](https://github.com/jacobastorga/web-citation-fact-checker)
> **Stack:** Python, BeautifulSoup4, Requests, Regex Parsing
* Automated verification pipeline that cross-references AI-generated claims and URLs against live web sources.
* Extracts cited references, detects broken links / 404s, parses source HTML content, and flags hallucinated or misleading citations in technical research outputs.

---

## 🏛️ Computational Science & AI Benchmark Architectures

### 1. [Computational Physics & Mathematics AI Benchmarks (`computational-physics-benchmarks`)](https://github.com/jacobastorga/computational-physics-benchmarks)
> **Stack:** Python, NumPy, SciPy (`solve_bvp`, `sparse.linalg`), SymPy, PyTest
* A research-grade computational evaluation suite designed to benchmark frontier foundation models on complex physical and mathematical reasoning tasks (2D Advection-Diffusion, Elastoplasticity, Nonlinear Beam Buckling).

### 2. [Autonomous Mechanical Agent Evaluation & Benchmark Harness (`mech-agent-eval-harness`)](https://github.com/jacobastorga/mech-agent-eval-harness)
> **Stack:** Python, Docker, CalculiX, FreeCAD API, Automated Verification Logic
* A benchmarking harness built to test and evaluate autonomous coding and engineering agents on multi-constraint mechanical design challenges, catching non-physical rigid-body stiffening and membrane cheats.

### 3. [Open-Source Structural FEA & Automated Convergence Pipeline (`open-fea-mesh-optimizer`)](https://github.com/jacobastorga/open-fea-mesh-optimizer)
> **Stack:** Python, FreeCAD OpenCASCADE, Gmsh API, CalculiX (`ccx`), ParaView
* Automated computational pipeline generating parametric B-Rep CAD geometry, building conformal 10-node quadratic tetrahedral meshes (`C3D10`), and verifying convergence via the ASME V&V 20 Grid Convergence Index (GCI).

---

## 📐 Engineering & Systems Philosophy

> *"In automated software engineering and AI evaluation, the objective is not merely matching an empirical text output, but verifying that the underlying AST complexity, tool-calling schemas, and causal execution graphs are rigorously sound and free from reward hacking."*

---

### 📫 Connect
* **LinkedIn:** [linkedin.com/in/jacob-astorga-895405416](https://www.linkedin.com/in/jacob-astorga-895405416/)
* **GitHub:** [@jacobastorga](https://github.com/jacobastorga)
* **Focus Areas:** AI Training & Alignment (RLHF / DPO), Agentic Tool Calling, Code Evaluation Benchmarks, Computational Modeling
