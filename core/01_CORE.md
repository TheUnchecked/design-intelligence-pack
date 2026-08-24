# Design Intelligence Pack — Core

## Purpose

Design Intelligence Pack (DIP) is a vendor-neutral framework for AI-assisted design reasoning.

It helps an AI system:

- understand a design problem before producing an output;
- make explicit design decisions;
- apply consistent visual and UX principles;
- identify weaknesses and anti-patterns;
- critique its own output;
- validate the result before considering the work complete.

DIP is not a design generator.

It is a **design reasoning and quality framework**.

---

## Core Principle

**Think → Define → Design → Evaluate → Improve**

Never jump directly from a vague request to a final design.

Before producing an output, determine:

1. What are we building?
2. Who is it for?
3. What must the user understand or accomplish?
4. What constraints exist?
5. What design decisions are required?
6. How will the result be evaluated?

---

## Operating Principles

### 1. Purpose Before Decoration

Every visual decision must serve a communication, usability, brand, or business purpose.

Do not add elements simply because they look attractive.

### 2. Hierarchy Before Detail

Establish information hierarchy before styling individual components.

The user should understand:

- what matters most;
- what matters next;
- what action is expected;
- what information is secondary.

### 3. Simplicity Before Complexity

Prefer the simplest solution that satisfies the requirement.

Avoid unnecessary:

- components;
- animation;
- decorative UI;
- interactions;
- visual variation.

### 4. Consistency Before Novelty

A coherent system is more valuable than isolated creative effects.

Reuse established:

- typography;
- spacing;
- colors;
- components;
- interaction patterns;
- visual language.

### 5. Content Drives Design

Design must accommodate the actual content.

Do not create layouts that only work with idealized placeholder text.

### 6. Accessibility Is a Requirement

Accessibility is part of the design process, not a final optional check.

Consider:

- contrast;
- typography;
- keyboard interaction;
- focus states;
- semantic hierarchy;
- readable content;
- motion sensitivity;
- responsive behavior.

### 7. Responsive by Design

Do not treat mobile as a smaller desktop.

Design must adapt to:

- screen size;
- interaction method;
- content density;
- available space;
- touch targets;
- information priority.

### 8. Explainable Decisions

Important design decisions should have a reason.

For every significant decision, be able to answer:

**Why this solution?**

---

## Decision Framework

For every significant design decision, evaluate:

### PURPOSE
What problem does this solve?

### USER
Who benefits from this decision?

### CONTEXT
Where and when is it experienced?

### HIERARCHY
What does this decision make more or less important?

### CONSISTENCY
Does it follow the existing design system?

### ACCESSIBILITY
Does it introduce usability barriers?

### RESPONSIVENESS
Does it remain effective across contexts?

### COMPLEXITY
Does the complexity justify the benefit?

---

## AI Behavior

When operating with this framework, the AI should:

### Before designing

- identify missing requirements;
- establish assumptions;
- define priorities;
- identify constraints;
- determine relevant design principles.

### While designing

- prioritize hierarchy;
- maintain consistency;
- minimize unnecessary complexity;
- consider accessibility;
- consider responsive behavior;
- explain significant decisions.

### After designing

- critique the result;
- identify weaknesses;
- prioritize issues by impact;
- propose corrections;
- validate the revised result.

---

## Priority Model

When multiple design problems exist, prioritize them in this order:

1. Usability
2. Accessibility
3. Information hierarchy
4. Content clarity
5. Responsive behavior
6. Consistency
7. Visual refinement
8. Decoration

Never polish a visual detail while a higher-priority usability problem remains unresolved.

---

## Quality Threshold

A design should not be considered complete merely because it:

- looks polished;
- follows current trends;
- contains a complete UI;
- satisfies the initial prompt.

A design is complete when it is:

**Useful + Understandable + Accessible + Consistent + Responsive + Intentional**

---

## Output Rule

When asked to design something, first establish:

- Objective
- Audience
- Context
- Requirements
- Constraints
- Design direction
- Success criteria

Then proceed to design.

When asked to critique or audit an existing design, follow:

**Observe → Identify → Explain → Prioritize → Recommend → Validate**

Do not invent problems that cannot be supported by the available evidence.

---

## Independence

Design Intelligence Pack is vendor-neutral.

It must not depend on:

- Claude;
- Microsoft Copilot;
- ChatGPT;
- Gemini;
- GitHub Copilot;
- a specific IDE;
- a specific programming language;
- a specific design application.

Any AI system capable of reading and following structured Markdown instructions should be able to use this framework.