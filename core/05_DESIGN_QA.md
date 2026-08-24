# Design Intelligence Pack — Design QA

## Purpose

Design QA is the final validation layer of the Design Intelligence Pack.

It evaluates whether a design satisfies its intended purpose before delivery.

Design QA is not visual preference.

It is evidence-based evaluation.

---

## QA Process

Follow this sequence:

**Observe → Evaluate → Prioritize → Recommend → Validate**

Do not begin by proposing solutions.

First identify what actually exists.

---

## 1. Product Alignment

Verify:

- Does the design support the stated business objective?
- Does it address the intended audience?
- Is the primary user goal clear?
- Are important requirements represented?
- Are unnecessary elements present?

### Result

**Pass / Needs Review / Fail**

---

## 2. Information Hierarchy

Verify:

- Is the primary message immediately identifiable?
- Is secondary information visually subordinate?
- Are sections logically ordered?
- Are important actions discoverable?
- Is visual emphasis consistent with importance?

---

## 3. UX

Verify:

- Can users accomplish the primary task?
- Are interactions predictable?
- Are actions clearly communicated?
- Is feedback provided?
- Are errors understandable?
- Can users recover from mistakes?
- Is unnecessary friction present?

---

## 4. Visual Design

Verify:

### Typography

- hierarchy;
- readability;
- consistency;
- scale;
- line length.

### Color

- hierarchy;
- contrast;
- semantic meaning;
- consistency.

### Layout

- alignment;
- spacing;
- composition;
- density;
- consistency.

### Components

- consistency;
- states;
- sizing;
- interaction patterns.

---

## 5. Accessibility

Check:

- color contrast;
- text readability;
- semantic hierarchy;
- keyboard accessibility;
- focus visibility;
- interactive target size;
- non-color indicators;
- motion sensitivity;
- accessible names and labels.

If accessibility cannot be verified from the available evidence, explicitly state that it requires further validation.

Never claim accessibility compliance without sufficient evidence.

---

## 6. Responsive Design

Evaluate the experience across relevant contexts.

Check:

- mobile;
- tablet;
- desktop;
- narrow viewport;
- wide viewport.

Verify:

- content priority;
- navigation;
- typography;
- spacing;
- images;
- controls;
- forms;
- tables;
- overflow;
- touch interaction.

---

## 7. Content Resilience

Test conceptually against:

- long headings;
- short headings;
- long paragraphs;
- missing content;
- unexpected content;
- translated content;
- large numbers;
- empty states;
- error states.

The design should not depend on ideal placeholder content.

---

## 8. Consistency

Check consistency across:

- typography;
- colors;
- spacing;
- components;
- terminology;
- interactions;
- states;
- navigation.

Identify repeated patterns that behave differently without justification.

---

## 9. Anti-Pattern Detection

Compare the design against:

`04_ANTI_PATTERNS.md`

Only report patterns supported by evidence.

For every detected issue provide:

```text
PATTERN
EVIDENCE
IMPACT
SEVERITY
RECOMMENDATION
CONFIDENCE