# AIDDM Methodology Overview v1.0

## 1. Introduction

AIDDM (AI Document-Driven Methodology) is a unified software development methodology designed for the AI era, where **documents, code, and tests remain fully synchronized** through automated AI-assisted processes and verifiable SDK tooling.

AIDDM establishes a development environment in which:
- Every artifact is traceable  
- Every step is auditable  
- Every document is verifiable  
- Every loop produces predictable output  
- AI becomes a first-class development participant  

AIDDM is built upon a structured **Document Chain** and a well-defined **Multi-Loop / Multi-Cycle Development Model**, supported by the **AIDDM SDK**, **MCP Server**, and **Tooling Framework**.

## 2. Core Principles of AIDDM

### P1 — Document First

Documents are the source of truth.

SRS → SDS → STS → Code → Test → ACR → TR form a closed, verifiable document chain.

### P2 — AI-Assisted, Human-Supervised

AI writes, generates, reviews, validates, and maintains documents, code, and tests.
Humans supervise, approve, and define high-level intent.

### P3 — Fully Verifiable Development

Every output must be “provable” via validation rules in the SDK:

- SRS/SDS consistency
- SDS/Code mapping
- STS/Test coverage
- ACR acceptance alignment

### P4 — Continuous Document Synchronization

Documents evolve together through cycles, ensuring no drift between requirement, design, test, and implementation.

### P5 — Governance Through Versioning

AIDDM enforces version alignment between

SRS / SDS / STS / Code / TR / ACR

to maintain system integrity.

## 3. Document-Driven Development (DDD)

AIDDM’s foundation is Document-Driven Development, where:

- Requirements describe behavior (SRS)
- Design describes structure (SDS)
- Tests describe verification (STS)
- Code implements SDS
- ACR validates acceptance
- TR records execution

Every layer references, verifies, and constrains the next layer.

AIDDM ensures no code exists without a source requirement.

## 4. Document Chain

AIDDM standardizes the full document lineage:

SRS → SDS → STS → Code → Test → ACR → TR → Version

### 4.1 SRS — Software Requirement Specification

Defines what the system must do.

### 4.2 SDS — Software Design Specification

Defines how the system must behave and be structured.

### 4.3 STS — Software Test Specification

Defines how the design is verified.

### 4.4 Code

Implementation generated or assisted by AI under SDS constraints.

### 4.5 Test

Executable validation matching STS.

### 4.6 ACR — Acceptance Criteria Report

AI-assisted acceptance validation.

### 4.7 TR — Test Report

Runtime execution outcome.

### 4.8 VDP — Version Development Plan

Defines loop structure, scope, variants, multi-version governance.

## 5. Multi-Loop / Multi-Cycle Model

AIDDM organizes work into:

**Loop** = macro iteration (L01, L02, …)  
Defines one complete development evolution cycle.

**Cycle** = micro iteration within a loop  
Plan → Document → Code → Test → Verify → Commit.

This model provides:
- Predictable iteration
- Continuous AI-assisted refinement
- Strict check-pointing and freeze points
- Multiple versions evolving in parallel (multi-version governance)

## 6. AI-Assisted Lifecycle

AI participates in every step:

| Phase        | AI Role                  | Human Role            |
| ------------ | ------------------------ | --------------------- |
| Requirement  | Generate draft SRS       | Approve intent        |
| Design       | Generate SDS             | Validate design logic |
| Testing      | Generate STS & test code | Confirm coverage      |
| Coding       | Skeleton + refinement    | Domain correctness    |
| Verification | Auto-check consistency   | Approve release       |
| Release      | Auto-generate TR/ACR     | Final approval        |

AIDDM SDK acts as the verification engine ensuring correctness.

## 7. AIDDM Governance Model

AIDDM defines a governance structure ensuring:

- Document version alignment
- Development transparency
- Controlled evolution
- Freeze rules for release cycles
- Multi-version maintenance capability

### 7.1 Document Version Alignment Rule

All documents in one loop must share the same major.minor version.
Patch version denotes intra-loop refinement.

### 7.2 Freeze Points

SRS freeze → SDS freeze → STS freeze → Release freeze

### 7.3 Traceability Requirements

All documents must reference prior chain artifacts.

## 8. Versioning Structure

All documents share the same major.minor version within a loop.

```
SRS 1.2.x
SDS 1.2.x
STS 1.2.x
Code 1.2.x
ACR 1.2.x
TR 1.2.x
```

This ensures the entire chain is both audit-ready and machine-verifiable.

## 9. Integration With SDK, MCP, CE

AIDDM Methodology is fully integrated with:

**AIDDM SDK**

- CLI for verification
- Document consistency check
- Template generation
- AI integration hooks
- Automated report generation

**AIDDM MCP Server**

The bridge between:

- IDE (VSCode)
- AI Agents (e.g., ChatGPT / Claude)
- SDK backend

**AIDDM-CE**

Community-driven open-source reference platform implementing AIDDM methodology.

**AIDDM Marketplace**

Extensible ecosystem for plugins, frameworks, domain packs.

## 10. Summary

AIDDM establishes a new era of software development:

- AI-driven
- Document-centered
- Fully verifiable
- Multi-version governance
- Auditable at every step

It creates a development ecosystem in which:

- AI accelerates
- SDK verifies
- Methodology governs
- Developers supervise and approve

AIDDM is the foundation of the next generation of software engineering.
