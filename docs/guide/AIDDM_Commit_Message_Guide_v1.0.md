# AIDDM Commit Message Guide v1.0

A standardized commit message format ensures clarity, traceability, and consistent governance across all AIDDM repositories.  
This guide defines the official commit message rules for Methodology, SDK, MCP, CE, and Marketplace.

---

# 📌 1. Commit Message Structure

AIDDM adopts a **tagged commit** format:

```
[Tag] Summary of change
```

- **Tag** = change category  
- **Summary** = short, clear description (max 72 chars)

Example:

```
[Doc] Add SRS template section for user login
```

---

# 📌 2. Allowed Commit Tags

| Tag | Usage |
|-----|-------|
| **[Doc]** | Document content changes (SRS/SDS/STS/VDP/Whitepaper) |
| **[Spec]** | Methodology standards & specification updates |
| **[Template]** | File templates added/modified (SRS/SDS/STS/ACR…) |
| **[Guide]** | README, tutorials, and user-facing guides |
| **[Governance]** | Workflow, audit rules, compliance documents |
| **[Structure]** | Folder restructuring / project organization |
| **[Fix]** | Typos, formatting, minor fixes |
| **[Refactor]** | Significant restructuring without content changes |
| **[Assets]** | Images, diagrams, banners, logos |
| **[Release]** | Version tags, release notes, changelog updates |

---

# 📌 3. Examples by Category

### 📝 **[Doc] Document Update**
```
[Doc] Add AIDDM Overview v1.0 introduction
[Doc] Update SDS structure for CE module design
```

### 📐 **[Spec] Methodology Standard**
```
[Spec] Add Document Chain cross-validation rules
[Spec] Update lifecycle definition for multi-loop model
```

### 🧩 **[Template] Template Creation**
```
[Template] Create STS template basic structure
[Template] Add VDP template timeline section
```

### 📘 **[Guide] Guides & README**
```
[Guide] Add installation steps to SDK README
[Guide] Update methodology folder index
```

### 🛡 **[Governance] Compliance Rules**
```
[Governance] Add audit flow diagram
[Governance] Define document approval stages
```

### 📁 **[Structure] Project Structure**
```
[Structure] Reorganize lifecycle documentation folders
[Structure] Move templates into docs/templates directory
```

### 🐞 **[Fix] Bug or Error Corrections**
```
[Fix] Correct terminology inconsistencies in Versioning Guide
[Fix] Fix broken link in README
```

### 🔧 **[Refactor] Non-functional changes**
```
[Refactor] Consolidate architecture descriptions
[Refactor] Normalize section headings across files
```

### 🎨 **[Assets] Images / Diagrams**
```
[Assets] Add AIDDM Document Chain diagram
[Assets] Update methodology banner for dark mode
```

### 🏁 **[Release] Version-related**
```
[Release] Tag methodology v1.0.0
[Release] Publish CE alpha roadmap
```

---

# 📌 4. Commit Message Rules

### ✔ Keep summary < 72 chars  
### ✔ Use ONE tag per commit  
### ✔ English only  
### ✔ Present tense  
### ✔ Keep commits atomic (one logical change per commit)

---

# 📌 5. Preferred Workflow

1. Write / edit content  
2. `git add .`  
3. Commit with correct tag  
4. Push  
5. Open PR if collaborative repo  

---

# 📌 6. Quick Reference Table

```
[Doc]       → Document content
[Spec]      → Methodology standard
[Template]  → Templates
[Guide]     → Guide / README
[Governance]→ Governance rules
[Structure] → File / directory structure
[Fix]       → Minor fixes
[Refactor]  → Reorganization
[Assets]    → Images / diagrams / logos
[Release]   → Version tags
```

---

# 📌 7. Recommended First Commit for New Repo

```
[Structure] Initialize methodology repository structure
```

---

# 📌 8. Recommended Follow-up Commits

```
[Doc] Add initial methodology documents
[Template] Add base templates for SRS/SDS/STS
[Spec] Add Document Chain Specification draft
```

---

# ✔ End of AIDDM Commit Message Guide v1.0
