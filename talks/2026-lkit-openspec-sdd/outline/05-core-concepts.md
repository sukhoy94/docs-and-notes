# Section 5: Core Concepts

## Slide 19 — Specs

**Specs = Requirements + Scenarios**

Plain Markdown files defining what the system SHALL do.

```markdown
## Requirements
- SHALL support light and dark themes
- SHALL persist user preference

## Scenarios
- WHEN user toggles theme THEN UI updates immediately
- WHEN user reopens app THEN last theme is restored
```

---

## Slide 20 — Changes

**A Change = A Self-Contained Proposal**

```
openspec/changes/add-dark-mode/
  ├── proposal.md
  ├── design.md
  ├── tasks.md
  └── specs/
```

Everything about one change lives in one folder.

---

## Slide 21 — Proposals

**`proposal.md` — The Why and What**

- What problem are we solving?
- What is in scope?
- What is explicitly OUT of scope?

The proposal is the contract between human and AI.

---

## Slide 22 — Design

**`design.md` — The How**

- Technical approach
- Architecture decisions
- Trade-offs considered

Written by AI, reviewed by human.

---

## Slide 23 — Tasks

**`tasks.md` — The Checklist**

```markdown
- [ ] Add CSS custom properties for theme colors
- [ ] Create ThemeToggle component
- [ ] Add localStorage persistence
- [ ] Update all components to use theme variables
- [ ] Add tests for theme switching
```

Discrete, implementable units of work.

---

## Slide 24 — The Golden Rule

**"AI creates artifacts.**
**Human reviews.**
**AI implements."**

Large text. Centered. Three lines.
This is the core loop of OpenSpec.
