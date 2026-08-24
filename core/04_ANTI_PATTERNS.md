# Design Intelligence Pack — Anti-Patterns

## Purpose

Identify recurring design patterns that reduce usability, clarity, accessibility, consistency or perceived quality.

An anti-pattern is not automatically wrong.

Evaluate it in context before recommending a change.

---

## 1. Generic AI Aesthetic

### Symptoms

- generic modern SaaS appearance;
- predictable layouts;
- excessive rounded cards;
- identical component patterns;
- generic gradients;
- interchangeable visual identity.

### Risk

The interface becomes visually indistinguishable from thousands of AI-generated products.

### Check

Ask:

- Does the design reflect the actual brand?
- Is there a recognizable visual identity?
- Are design choices intentional?

---

## 2. Excessive Rounded Cards

### Symptoms

- cards everywhere;
- cards inside cards;
- excessive border radius;
- unrelated content grouped into containers.

### Risk

Creates visual clutter and weakens hierarchy.

### Prefer

Use containers when grouping provides meaningful structure.

---

## 3. Gradient Overuse

### Symptoms

- gradients used as decoration;
- purple/blue AI-style gradients;
- gradients behind every section;
- gradients used instead of hierarchy.

### Risk

Creates visual noise and generic branding.

### Prefer

Use gradients only when they serve identity, depth or communication.

---

## 4. Excessive Glassmorphism

### Symptoms

- excessive blur;
- transparent panels;
- low-contrast text;
- decorative glass surfaces.

### Risk

Reduces readability and introduces unnecessary visual complexity.

---

## 5. Excessive Shadows

### Symptoms

- shadows on every component;
- multiple shadow levels without hierarchy;
- heavy elevation effects.

### Risk

Creates visual noise and artificial depth.

### Prefer

Use elevation only when it communicates layering or interaction.

---

## 6. Everything Is a CTA

### Symptoms

- multiple primary buttons;
- several competing actions;
- excessive accent colors.

### Risk

Users cannot identify the intended next action.

### Prefer

Establish one clear primary action where appropriate.

---

## 7. Weak Typography Hierarchy

### Symptoms

- similar heading and body sizes;
- excessive font weights;
- arbitrary type sizes;
- tiny supporting text.

### Risk

Users cannot quickly understand information priority.

---

## 8. Decorative Icons Without Meaning

### Symptoms

- icons added to every heading;
- decorative icon boxes;
- icons without semantic value.

### Risk

Adds visual noise without improving comprehension.

### Prefer

Use icons when they communicate meaning or improve recognition.

---

## 9. Nested Containers

### Symptoms

```text
Section
└── Card
    └── Card
        └── Card