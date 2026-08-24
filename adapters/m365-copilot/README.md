# M365 Copilot Adapter

## Purpose

This adapter defines how to use the Design Intelligence Pack with Microsoft 365 Copilot Notebooks.

The Design Intelligence Pack remains vendor-neutral.

This adapter only defines the recommended way to provide the framework to Microsoft 365 Copilot.

---

## 1. Knowledge Structure

A Copilot Notebook should contain the relevant Design Intelligence Pack knowledge as references.

Recommended structure:

```text
DESIGN INTELLIGENCE NOTEBOOK
│
├── MASTER
│   └── DESIGN_INTELLIGENCE_MASTER
│
├── CORE
│   ├── CORE
│   ├── VISUAL DESIGN
│   ├── UX DESIGN
│   ├── ANTI-PATTERNS
│   └── DESIGN QA
│
├── BRAND
│   └── BRAND GUIDELINES
│
├── MODULES
│   └── Relevant output module
│
└── PROJECT CONTEXT
    ├── Product Brief
    ├── Design Brief
    ├── Requirements
    └── Project References
```

---

## 2. Recommended Reference Priority

When multiple references are available, use this priority:

1. Project-specific requirements
2. Official brand guidelines
3. Design Intelligence Master
4. Relevant Core principles
5. Relevant specialized module
6. Templates
7. Additional references

Project constraints and official brand requirements must not be overridden by generic recommendations.

---

## 3. Operating Instruction

When using the Design Intelligence Pack:

* use the Master as the primary reasoning framework;
* use Core documents as design knowledge;
* use the relevant module for the output format;
* use Brand Guidelines when available;
* use project references as contextual evidence;
* distinguish facts from assumptions;
* identify unknowns;
* do not invent missing information.

---

## 4. Recommended Workflow

### Step 1 — Understand

Analyze:

* objective;
* audience;
* context;
* requirements;
* constraints;
* success criteria.

### Step 2 — Structure

Define:

* information hierarchy;
* narrative;
* content structure;
* priorities.

### Step 3 — Design

Apply:

* Core principles;
* Brand Guidelines;
* relevant module;
* accessibility requirements.

### Step 4 — Create

Produce the requested artifact.

### Step 5 — Critique

Evaluate the result independently.

### Step 6 — QA

Validate:

* objective;
* audience;
* content;
* design;
* accessibility;
* brand;
* format;
* consistency.

### Step 7 — Improve

Address the highest-impact issues first.

---

## 5. Prompt Pattern

A useful Copilot instruction is:

```text
Use the Design Intelligence Pack as the design and reasoning framework.

Use:
- the Master as the primary framework;
- the relevant Core references as design knowledge;
- the applicable Module for the output format;
- Brand Guidelines as visual constraints;
- project references as contextual evidence.

Before producing the final artifact:
1. understand the objective;
2. identify the audience;
3. identify constraints;
4. establish information hierarchy;
5. select an appropriate structure;
6. identify assumptions and unknowns.

Do not invent facts.

After producing the artifact:
1. critique it;
2. identify high-impact issues;
3. validate it against the framework;
4. propose improvements.
```

---

## 6. Using Different Modules

Only load the modules relevant to the current task.

Examples:

### Presentation

Use:

* Master
* Core
* Brand
* Presentation module

### Report

Use:

* Master
* Core
* Brand
* Report module

### Document

Use:

* Master
* Core
* Brand
* Document module

### Web

Use:

* Master
* Core
* Brand
* Web module

Avoid loading unnecessary modules when they are not relevant.

---

## 7. Project Context

Project-specific information should remain separate from the Design Intelligence Pack.

Examples:

* business requirements;
* technical documentation;
* source data;
* assessment results;
* stakeholder requirements;
* project-specific brand information.

The Pack defines **how to reason**.

Project references define **what to reason about**.

---

## 8. Copilot Notebook Principle

The Notebook should act as a contextual workspace.

The Design Intelligence Pack provides the methodology.

Project references provide the evidence.

Copilot performs the reasoning and creation.

```text
DESIGN INTELLIGENCE
        +
PROJECT CONTEXT
        ↓
      COPILOT
        ↓
   ARTIFACT
        ↓
   CRITIQUE + QA
```

---

## 9. Important Limitation

The Design Intelligence Pack does not guarantee correct output.

AI-generated results must still be reviewed by a qualified human.

The framework improves reasoning consistency, structure and quality assurance.

It does not replace professional judgment.
