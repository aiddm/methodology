# AIDDM Methodology — Official Documentation

<p align="center">
  <img src="assets/banners/methodology_banner.png" width="100%" alt="AIDDM Methodology Banner" />
</p>

AIDDM (AI Document-Driven Methodology) provides a complete, verifiable, AI-assisted development framework based on structured documents, lifecycle governance, and automated validation.

This repository contains the core specifications of the AIDDM methodology.

---

# 📚 Core Specifications

## 1. Overview  
High-level principles, philosophy, and conceptual structure of the methodology.

👉 `docs/spec/overview.md`  
(Describes the motivation, pillars, and architecture of AIDDM.)

---

## 2. Document Chain Specification  
Defines **WHAT documents exist**, how they connect, and the structural/validation rules.

👉 `docs/spec/document_chain.md`

Covers:

- SRS, SDS, STS, Code, Test, TR, ACR, VDP
- Metadata/frontmatter requirements
- Cross-document traceability
- Mandatory linking rules (SRS→SDS→STS→Code→Test→TR→ACR)
- Version alignment rules
- Patch version downstream ≥ upstream rule
- AI & SDK validation integration

---

## 3. Development Lifecycle Specification  
Defines **HOW development progresses** across Loops and Cycles.

👉 `docs/spec/lifecycle.md`

Covers:

- Loop model (L01, L02, …)
- Cycle model (C1, C2, …)
- High-level lifecycle flow diagram
- Cycle workflow (Plan → Document → Code → Test → Verify → Commit)
- Freeze points (SRS Freeze, SDS Freeze, STS Freeze, Release Freeze)
- Hotfix cycle (C-HF1 etc.)
- Version governance (major.minor alignment)
- Patch version progression (downstream ≥ upstream)
- Governance interaction points
- AI-assisted authoring & SDK validation gates

---

## 4. Governance Model  
Rules, approvals, checkpoints, and lifecycle gates.

👉 `docs/spec/governance_model.md`  
*(To be completed – Issue #4)*

---

## 5. Template Suite  
Standardized templates for SRS/SDS/STS/VDP/ACR/TR.

👉 `docs/templates/`  
*(To be completed – Issue #5)*

---

## 6. Diagram Set  
Mermaid + SVG diagrams referenced by all specifications.

👉 `assets/diagrams/`  
*(To be completed – Issue #6)*

---

# 📁 Repository Structure

```mathematica
methodology/
├─ README.md ← (this file)
├─ docs/
│ └─ spec/
│ ├─ overview.md
│ ├─ document_chain.md
│ ├─ lifecycle.md
│ ├─ governance_model.md
│ └─ ...
│
├─ docs/templates/
│ ├─ srs_template.md
│ ├─ sds_template.md
│ ├─ sts_template.md
│ ├─ vdp_template.md
│ ├─ acr_template.md
│ └─ tr_template.md
│
└─ assets/
└─ diagrams/
├─ document_chain.mmd
├─ lifecycle.mmd
├─ governance.mmd
└─ ...
```


---

# 🔗 Cross-Document Relationships

- **Document Chain ↔ Lifecycle**  
  - Lifecycle defines the *process* by which the Document Chain evolves.
- **Lifecycle ↔ Governance**  
  - Governance defines rules & approvals for each lifecycle stage.
- **Document Chain ↔ Templates**  
  - Templates implement the structural rules of the Document Chain.
- **SDK / MCP ↔ All Specifications**  
  - SDK enforces structure, linkage, and version consistency.

---

# 🧩 Status

| Specification    | Status        |
| ---------------- | ------------- |
| Overview         | ✔ Complete    |
| Document Chain   | ✔ Complete    |
| Lifecycle        | ✔ Complete    |
| Governance Model | ⏳ In Progress |
| Templates        | ⏳ Pending     |
| Diagram Set      | ⏳ Pending     |

---

# 🚀 Next Steps

- Finalize **Governance Model v1.0**  
- Generate Templates v1.0  
- Produce Diagrams (Issue #6)  
- Prepare Multi-language Editions (zh-TW, zh-CN, ja, ko)  
- Integrate into AIDDM-CE & SDK

---

# © AIDDM — AI Document-Driven Methodology
Built for international, AI-enhanced, reproducible software development.
