# Section 7: Real Example — "Add Dark Mode"

## Slide 30 — The Scenario

**We want to add dark mode to our web app.**

Without specs: "Hey AI, add dark mode" → unpredictable result.
With OpenSpec: structured, reviewed, implemented step by step.

---

## Slide 31 — The Proposal

**`proposal.md` snippet:**

```markdown
## Summary
Add dark mode support with user preference persistence.

## In Scope
- Theme toggle component
- CSS custom properties for theming
- localStorage persistence

## Out of Scope
- System preference detection (future change)
- Per-page theme overrides
```

Clear boundaries. AI knows what NOT to do.

---

## Slide 32 — The Design

**`design.md` snippet:**

```markdown
## Approach
Use CSS custom properties on :root.
Toggle class on <html> element.

## Decision: CSS Variables vs CSS-in-JS
CSS variables chosen for:
- Zero runtime cost
- Works with existing stylesheets
- No library dependency
```

Decisions are documented, not buried in code comments.

---

## Slide 33 — The Tasks

**`tasks.md` snippet:**

```markdown
- [ ] Define color tokens in :root and [data-theme="dark"]
- [ ] Create ThemeToggle component with icon
- [ ] Wire toggle to localStorage read/write
- [ ] Migrate hardcoded colors to CSS variables
- [ ] Add unit tests for ThemeToggle
```

Each task is independently implementable and verifiable.

---

## Slide 34 — After Archive

**Before:**
```
specs/ (no theming spec)
```

**After:**
```
specs/theming/spec.md
  - SHALL support light and dark themes
  - SHALL persist user preference in localStorage
```

The spec becomes the permanent record.
Next time anyone touches theming, the spec is there.
