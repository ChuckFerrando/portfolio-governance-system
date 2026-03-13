![License: MIT](https://img.shields.io/badge/License-MIT-green.svg) ![Status](https://img.shields.io/badge/Status-Stable-blue.svg) 
![Type](https://img.shields.io/badge/Type-Portfolio%20Governance-purple.svg) 
![Pillar](https://img.shields.io/badge/Pillar-3%20Portfolio%20Governance-black.svg) 
![Product Leadership OS](https://img.shields.io/badge/Product%20Leadership-Operating%20System-black.svg) 

# Portfolio Governance System 

This repository documents **Pillar 3** of the **Product Leadership Operating System (PLOS)** and defines how organizations govern investment decisions through evaluation, prioritization, sequencing, funding, review, and rebalancing across the portfolio. 

Where the **Product Leadership Systems Architecture (PLSA)** defines the canonical five-system architecture, the **Portfolio Governance System** defines the system responsible for converting strategic intent into governed portfolio action. 

This repository is a navigation and orientation layer for the Pillar 3 governance library. 

It summarizes the purpose of the repository, shows how the major artifacts relate to one another, and helps readers understand how to navigate the supporting governance architecture. 

--- 

# Portfolio Governance Overview 

The **Portfolio Governance System** explains how organizations translate strategy into governed investment rather than relying on ad hoc prioritization or disconnected planning activity. 

It shows how organizations move from: **strategic direction → initiative evaluation → prioritization → funding → portfolio review → rebalancing** through a disciplined governance system. 

Within the broader **Product Leadership Operating System**, Pillar 3 is responsible for the system that governs investment decisions across the operating loop. 

In practical terms: **Strategy defines direction → Governance governs investment → Delivery executes work → Outcomes evaluate results → Learning informs adjustment** 

Decision Intelligence supports every stage of that loop. 

--- 

# Top-Level Portfolio Governance Diagram

```mermaid
flowchart TB

    A[Strategy Execution System]
    B[Portfolio Governance System]
    C[Product Delivery System]
    D[Customer Outcomes System]
    J[Learning and Strategic Adjustment]

    A -->|Strategic priorities and intent| B
    B -->|Governed investment decisions| C
    C -->|Execution evidence and progress| D
    D -->|Outcome evidence| J
    J -->|Strategic and portfolio adjustment| A

    E[Decision Intelligence System]
    E -.Decision support.-> B
    E -.Decision support.-> C
    E -.Decision support.-> D
    E -.Decision support.-> J

    F[Initiative Evaluation]
    G[Prioritization and Sequencing]
    H[Funding and Allocation]
    I[Portfolio Review and Rebalancing]

    F --> B
    G --> B
    H --> B
    I --> B
 ```

 --- 
 
# Repository Purpose

The purpose of this repository is to define the system through which strategic priorities become governed portfolio investment.

This repository focuses on the governance mechanisms required to:

- evaluate proposed initiatives
- prioritize competing investment options
- sequence work across portfolio constraints
- allocate funding and capacity
- govern tradeoffs and commitments
- review portfolio performance
- rebalance investments based on evidence

Taken together, these artifacts explain how organizations maintain disciplined investment governance across the broader operating system.

This repository does **not** redefine the architecture. It operates subordinate to the higher-precedence Pillar 1 architectural sources.

--- 

# Pillar 3 Artifact Map

```mermaid
flowchart TB

    ROOT[Portfolio Governance System]

    subgraph CANONICAL[Canonical Source]
        A1[Portfolio Governance System]
    end

    subgraph SUPPORTING[Planned Supporting Artifacts]
        B1[Portfolio Review Model]
        B2[Investment Decision Model]
        B3[Prioritization Framework]
        B4[Governance Decision Rights]
    end

    subgraph FRAMEWORKS[Planned Supporting Frameworks]
        C1[Portfolio Governance Maturity Model]
    end

    subgraph DIAGRAMS[Planned Supporting Diagram Artifacts]
        D1[Portfolio Governance System Diagram]
        D2[Governance Decision Flow Diagram]
        D3[Portfolio Review Cycle Diagram]
    end

    ROOT --> A1
    A1 --> B1
    A1 --> B2
    A1 --> B3
    A1 --> B4
    A1 --> C1
    A1 --> D1
    A1 --> D2
    A1 --> D3
``` 

--- 

# Core Repository Artifacts

This repository contains the core artifacts that define how organizations govern portfolio investment through evaluation, prioritization, sequencing, funding, review, and rebalancing.

## Canonical Source Artifact

- **Portfolio Governance System**  
  Defines the canonical Pillar 3 governance system used to translate strategy into governed portfolio action.

## Planned Supporting Artifacts

- **Portfolio Review Model**  
  Defines the recurring review structure used to assess portfolio commitments, performance, and change decisions.

- **Investment Decision Model**  
  Defines the governing logic used to evaluate, approve, defer, or reject investment choices.

- **Prioritization Framework**  
  Defines the structure used to compare competing initiatives and determine portfolio order and relative importance.

- **Governance Decision Rights**  
  Defines the allocation of decision authority across governance roles, forums, and review levels.

## Planned Supporting Frameworks

- **Portfolio Governance Maturity Model**  
  Defines how governance capability evolves from informal prioritization toward structured, evidence-based portfolio governance.

## Planned Supporting Diagram Artifacts

- **Portfolio Governance System Diagram**  
  Visualizes the role of the governance system within the canonical five-system architecture.

- **Governance Decision Flow Diagram**  
  Visualizes how investment decisions move from evaluation through approval, allocation, review, and adjustment.

- **Portfolio Review Cycle Diagram**  
  Visualizes the recurring review and rebalancing loop used to sustain portfolio governance over time.

--- 

# Repository Structure

This repository functions as an executive architecture library for **Pillar 3: Portfolio Governance System**.

Artifacts are organized into the following directories:

| Directory | Purpose |
|---|---|
| `architecture/` | Canonical governance system definitions, structural system artifacts, and foundational Pillar 3 architecture documents |
| `frameworks/` | Governance reference structures, maturity models, and supporting conceptual frameworks |
| `artifacts/` | Governance mechanisms, decision structures, prioritization artifacts, review models, and decision-rights definitions |
| `diagrams/` | Reusable visual artifacts that support interpretation of the governance system |

This structure keeps the repository navigable while preserving the distinction between canonical architecture, supporting frameworks, operating artifacts, and visual documentation.

--- 

# Relationship to the Product Leadership Operating System

Within the broader **Product Leadership Operating System (PLOS)**, this repository defines **Pillar 3: Portfolio Governance System**.

That distinction is essential:

- **PLOS** is the overall operating system and portfolio
- **PLSA** is the canonical systems architecture defined in Pillar 1
- **Pillar 3** defines the system responsible for governed investment and portfolio decision-making

In simple terms:

- **Strategy Execution System** defines direction
- **Portfolio Governance System** governs investment
- **Product Delivery System** executes approved work
- **Customer Outcomes System** evaluates realized results
- **Decision Intelligence System** supports decisions across the full architecture

This repository should therefore be read together with the Pillar 1 architecture repository and, where relevant, alongside Pillar 2 operating-model artifacts that explain how governance is run in practice. 

--- 

# Documentation Standard

All repositories in this portfolio follow a common architecture-documentation standard.

Key principles include:

- executive-level tone
- architecture-first framing
- canonical terminology preservation
- GitHub-compatible Mermaid diagrams
- clear distinction between canonical, supporting, derivative, and experimental artifacts
- README content that supports navigation without redefining architecture

This repository is intentionally **not**:

- a budgeting tutorial
- a project intake handbook
- a PMO process manual
- agile portfolio training content
- a blog-style governance essay

It is an executive portfolio governance architecture library within the **Product Leadership Operating System**.

--- 

# How To Navigate This Repository

Use this repository in the following order:

1. Start with **Portfolio Governance System** for the canonical Pillar 3 definition.
2. Review **Investment Decision Model** and **Prioritization Framework** to understand how investment choices are evaluated and ordered.
3. Review **Governance Decision Rights** to understand how authority is distributed across governance decisions.
4. Review **Portfolio Review Model** to understand how portfolio commitments are reassessed and adjusted over time.
5. Review **Portfolio Governance Maturity Model** to understand governance capability progression.
6. Use the supporting diagram artifacts for visual orientation and cross-repository consistency.

This sequence preserves architectural precedence while improving interpretability.

--- 

# License 

This repository is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
