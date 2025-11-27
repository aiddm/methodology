# 📘 **AIDDM** Methodology — Document Index (Public Version)

*Version: Draft for Review*

*Purpose: Repository-wide index + community architecture overview*

This index lists all documents within the **AIDDM** Methodology Repository.
Some documents may be placeholders or under development — their presence allows contributors to understand the full conceptual and technical structure of the **AIDDM** ecosystem.

**AIDDM** follows a layered documentation model:


**Core Conceptual** → **Methodology Specification** → **Meta Semantic Model** → **Concrete Model** → **Format Models** → **Interface Specs** → **Implementation References** → **CE Templates**


Each layer is independent and clearly scoped, enabling community contributions without requiring deep knowledge of internal semantics.

---

## 🟥 Level 1 — Core Conceptual Layer

Documents defining **AIDDM**’s philosophy, vision, motivation, and high-level ecosystem ideas.

| File                                    | Description                                                                          |
| --------------------------------------- | ------------------------------------------------------------------------------------ |
| `conceptual/aiddm-whitepaper.md`        | Overview of **AIDDM**’s purpose, background, and long-term direction.                |
| `conceptual/aiddm-philosophy.md`        | Core document-driven and AI-assisted development philosophy.                         |
| `conceptual/aiddm-mission-statement.md` | Mission, intent, and foundational goals.                                             |
| `conceptual/aiddm-principles.md`        | Core principles similar to an Agile-style manifesto.                                 |
| `conceptual/aiddm-ecosystem-vision.md`  | Ecosystem model: semantic unity, format freedom, language neutrality, extensibility. |

---

## 🟦 Level 2 — Methodology Specification Layer

Formal rules, lifecycle definitions, and governance structures.

| File                               | Description                                               |
| ---------------------------------- | --------------------------------------------------------- |
| `spec/aiddm-overview.md`           | Complete overview of **AIDDM** methodology and structure. |
| `spec/aiddm-document-chain.md`     | Document graph, node types, link semantics.               |
| `spec/aiddm-lifecycle.md`          | Version → Stage → Cycle → Loop process.                   |
| `spec/aiddm-version-governance.md` | Versioning rules and alignment policies.                  |
| `spec/aiddm-glossary.md`           | Standardized terminology for the entire ecosystem.        |
| `spec/aiddm-best-practices.md`     | Writing, validation, and collaboration guidelines.        |

---

## 🟩 Level 3 — Meta Semantic Layer (Meta Model)

Defines the semantic core of **AIDDM**.
This layer does not specify formats or programming languages.

| File                                | Description                                                                   |
| ----------------------------------- | ----------------------------------------------------------------------------- |
| `meta/meta-model-spec.md`           | The semantic foundation of **AIDDM** (DocumentNode, Link, Operations, Graph). |
| `meta/document-node-spec.md`        | Semantic definition of document nodes.                                        |
| `meta/document-link-spec.md`        | Semantic definition of document links and dependency types.                   |
| `meta/document-frontmatter-spec.md` | Semantic meaning of frontmatter fields (not tied to any format).              |
| `meta/document-operations-spec.md`  | Validation, trace, derive, render, align—semantic definitions.                |

---

## 🟨 Level 4 — Concrete Model Layer (Intermediate Representation)

An implementation-friendly representation of the Meta Model.
This layer translates semantics into structured, language-agnostic data models.

| File                                    | Description                                   |
| --------------------------------------- | --------------------------------------------- |
| `concrete/concrete-document-model.md`   | IR version of DocumentNode.                   |
| `concrete/concrete-link-model.md`       | IR representation of link structures.         |
| `concrete/concrete-operations-model.md` | IR representation of operations & results.    |
| `concrete/concrete-schema-model.md`     | Base schema used to derive JSON/YAML/XML/etc. |

---

## 🟧 Level 5 — Format Model Layer (Representational Formats)

Format-specific models generated from the Concrete Model.
These are community-friendly and open to contributions.

| File                        | Description                                              |
| --------------------------- | -------------------------------------------------------- |
| `formats/markdown-model.md` | Markdown + Frontmatter structure (primary human format). |
| `formats/json-model.md`     | JSON schema representation of documents.                 |
| `formats/yaml-model.md`     | YAML representation.                                     |
| `formats/xml-model.md`      | XML tag structure for **AIDDM** documents.               |
| `formats/gui-model.md`      | *(Placeholder)* Visual/GUI representation model.         |

---

## 🟫 Level 6 — Interface Specification Layer (SDK / API Specs)

Language-agnostic contract definitions.

| File                                | Description                                                 |
| ----------------------------------- | ----------------------------------------------------------- |
| `interface/sdk-specification.md`    | Unified SDK behavior: parse, validate, trace, render, diff. |
| `interface/api-specification.md`    | REST/RPC contract for document operations.                  |
| `interface/cli-specification.md`    | AIDC CLI behavior specification.                            |
| `interface/mcp-integration-spec.md` | Interaction protocol for AI/MCP environments.               |

---

## 🟪 Level 7 — Implementation Reference Layer

Reference implementations (open source; optional).

| File / Folder          | Description                       |
| ---------------------- | --------------------------------- |
| `impl/sdk-python/`     | Python SDK reference.             |
| `impl/sdk-typescript/` | TypeScript SDK reference.         |
| `impl/verify-engine/`  | Validation engine implementation. |
| `impl/api-server/`     | Reference API server.             |
| `impl/cli/`            | AIDC CLI implementation.          |

---

## ⬛ Level 8 — CE Application Templates

Standard CE documents used by **AIDDM**-driven projects.

| File                        | Description                                       |
| --------------------------- | ------------------------------------------------- |
| `templates/srs-template.md` | Software Requirements Specification.              |
| `templates/sds-template.md` | Software Design Specification.                    |
| `templates/sts-template.md` | Software Test Specification.                      |
| `templates/vdp-template.md` | Version Development Plan.                         |
| `templates/tr-template.md`  | Test Report.                                      |
| `templates/acr-template.md` | Acceptance Criteria Report.                       |
| `templates/ce-guide.md`     | How to apply all templates in **AIDDM** projects. |

---

🟦 Notes for Contributors

1. Some documents are currently empty or draft-only.

    Their presence is intentional to help contributors understand the full layered architecture.

2. Community contributions are encouraged particularly in:

    - Format Models (JSON/YAML/XML/GUI)
    - SDK Implementations (any programming language)
    - Tooling integrations

3. Semantic rules are defined only in the Meta Model.

    All other layers derive from it and must remain consistent.
