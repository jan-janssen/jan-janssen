# Jan Janssen

I am a computational materials scientist working at the interface of **materials science, scientific workflows, high-performance computing, machine learning, and agentic AI**.

I lead the [Materials Informatics Group](https://www.mpie.de/5013829/matinf) at the [Max Planck Institute for Sustainable Materials](https://www.mpie.de), where we develop the methods and computational infrastructure needed to make materials simulations **reproducible, scalable, interoperable, and increasingly autonomous**.

> **Materials science → scientific workflows → HPC → machine learning → agentic science**

## Research

My research focuses on turning expert computational procedures into reusable scientific workflows that can be executed across computing environments, inspected by researchers, and increasingly orchestrated by AI agents.

Current research directions include:

- **Automated atomistic simulation and ab-initio thermodynamics**
- **Uncertainty quantification and convergence of electronic-structure calculations**
- **Machine-learned interatomic potentials and data-driven materials discovery**
- **Scientific workflow interoperability and provenance**
- **Scalable execution of Python workflows on HPC systems**
- **LLM-based agents for scientific simulation and autonomous discovery**

A recurring goal throughout this work is to connect individual simulation methods into transparent computational processes that can produce quantitative predictions and remain understandable to domain scientists.

## Scientific software and infrastructure

I contribute to and lead several open-source projects spanning scientific workflows, HPC execution, and materials simulation. **Reproducibility, automated testing, continuous integration, and sustainable software engineering are integral parts of this work.** Scientific software is treated as a research output rather than disposable glue code.

| Project | Role in the ecosystem | Publication | Coverage | GitHub Stars |
|---|---|---|---|---|
| [pyiron/pysqa](https://github.com/pyiron/pysqa) (2026) | Common interface to HPC queuing systems | [JOSS](https://doi.org/10.21105/joss.10961) | [![codecov](https://codecov.io/gh/pyiron/pysqa/graph/badge.svg?token=N753OWIAUW)](https://codecov.io/gh/pyiron/pysqa) | ![GitHub Repo stars](https://img.shields.io/github/stars/pyiron/pysqa) |
| [pyiron/executorlib](https://github.com/pyiron/executorlib) (2025) | Scale Python functions from local execution to HPC resources | [JOSS](https://doi.org/10.21105/joss.07782) | [![codecov](https://codecov.io/gh/pyiron/executorlib/graph/badge.svg?token=KFIO3R08H3)](https://codecov.io/gh/pyiron/executorlib) | ![GitHub Repo stars](https://img.shields.io/github/stars/pyiron/executorlib) |
| [jan-janssen/LangSim](https://github.com/jan-janssen/LangSim) (2025) | LLM agents for atomistic simulation | [Machine Learning: Science and Technology](http://doi.org/10.1088/2632-2153/ae011a) | — | ![GitHub Repo stars](https://img.shields.io/github/stars/jan-janssen/LangSim) |
| [pythonworkflow/python-workflow-definition](https://github.com/pythonworkflow/python-workflow-definition) (2025) | Interoperable representation of scientific workflows | [Digital Discovery](https://doi.org/10.1039/D5DD00231A) | [![codecov](https://codecov.io/github/pythonworkflow/python-workflow-definition/graph/badge.svg?token=3JXD1GN8LG)](https://codecov.io/github/pythonworkflow/python-workflow-definition) | ![GitHub Repo stars](https://img.shields.io/github/stars/pythonworkflow/python-workflow-definition) |
| [pyiron/pyiron](https://github.com/pyiron/pyiron) (2019) | Integrated environment for computational materials science | [Computational Materials Science](https://doi.org/10.1016/j.commatsci.2018.07.043) | — | ![GitHub Repo stars](https://img.shields.io/github/stars/pyiron/pyiron) |

Together, these projects address different layers of one problem:

**scientific method → reusable workflow → portable execution → HPC → AI-assisted orchestration**

## Materials Informatics Group

The [Materials Informatics Group](https://github.com/janssenlab) develops open scientific infrastructure and applies it to problems in computational materials science.

Our work combines:

- electronic-structure and atomistic simulation,
- thermodynamics and phase stability,
- machine learning,
- high-throughput and distributed computing,
- reproducible scientific workflows,
- and AI-assisted simulation.

The group GitHub organization serves as a curated entry point to our software, tutorials, lectures, and community activities:

**[github.com/janssenlab](https://github.com/janssenlab)**

## From simulation workflows to agentic science

A major direction of my current work is the transition from conventional workflow automation toward **agentic scientific workflows**.

Rather than asking an LLM to generate a monolithic simulation script, I am interested in systems in which agents operate on validated scientific building blocks and explicit workflows.

A typical loop can be expressed as:

**Scientific question → hypothesis → workflow construction → simulation → validation → explanation**

The objective is not only to automate scientific calculations, but to preserve:

- provenance,
- reproducibility,
- inspectability,
- physical constraints,
- and interaction with domain experts.

This allows AI systems to become part of the scientific workflow without hiding the computational process behind an opaque interface.

## Research collaboration

I am interested in collaborations where workflow and infrastructure expertise can complement strong domain knowledge.

Examples include collaborations in:

- **computational materials science** — automating and scaling DFT, MD, thermodynamic, and multiscale workflows;
- **experimental materials science** — linking simulations, experiments, and machine learning through reproducible workflows;
- **machine learning for materials** — dataset generation, MLIP workflows, uncertainty propagation, and validation;
- **AI for science** — providing scientific tools and workflow environments for autonomous agents;
- **high-performance computing** — developing realistic scientific workloads for distributed and exascale computing;
- **research software engineering** — improving interoperability, provenance, packaging, and sustainability of scientific software.

The central value I aim to contribute is the ability to turn scientific methods into **reusable computational capabilities** that can move from an individual research script to a scalable research infrastructure.

## Teaching and community

I regularly contribute tutorials and lectures on:

- scientific workflows,
- atomistic simulation,
- density functional theory,
- machine learning in materials science,
- and HPC execution.

Tutorial material from the Materials Informatics group is collected at the [Janssen Lab GitHub organization](https://github.com/janssenlab) and the [pyiron workshop organization](https://github.com/pyiron-workshop).

## Automation beyond materials science

I also maintain small open-source projects exploring automation of repetitive digital tasks.

| Project | Purpose | Coverage | GitHub Stars |
|---|---|---|---|
| [gmailsorter](https://github.com/jan-janssen/gmailsorter) | Automate sorting email into folders | [![codecov](https://codecov.io/github/jan-janssen/gmailsorter/graph/badge.svg?token=NWN0UINECM)](https://codecov.io/github/jan-janssen/gmailsorter) | ![GitHub Repo stars](https://img.shields.io/github/stars/jan-janssen/gmailsorter) |
| [pyauthenticator](https://github.com/jan-janssen/pyauthenticator) | Programmatic two-factor authentication workflows | [![codecov](https://codecov.io/github/jan-janssen/pyauthenticator/graph/badge.svg?token=K0VG71K9YI)](https://codecov.io/github/jan-janssen/pyauthenticator) | ![GitHub Repo stars](https://img.shields.io/github/stars/jan-janssen/pyauthenticator) |
| [conda-forge-contribution](https://github.com/jan-janssen/conda-forge-contribution) | Automate and analyze software packaging contributions | — | ![GitHub Repo stars](https://img.shields.io/github/stars/jan-janssen/conda-forge-contribution) |

These projects reflect the same general interest that drives my scientific work: **identify repetitive processes, make them explicit, and automate them in a transparent and reusable way.**

## Links

- [Materials Informatics Group](https://www.mpie.de/5013829/matinf)
- [Janssen Lab GitHub organization](https://github.com/janssenlab)
- [pyiron](https://github.com/pyiron)
- [Python Workflow Definition](https://github.com/pythonworkflow/python-workflow-definition)
- [Personal website](https://jan-janssen.com)
