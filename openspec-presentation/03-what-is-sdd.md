# Section 3: What is Specification-Driven Development?

## Slide 11 — Introducing SDD

**Specification-Driven Development**

Write formal specs BEFORE code.
But iterate on them — this is NOT waterfall.

Specs are living documents that evolve with the project.

---

## Slide 12 — SDD is NOT Waterfall

**Diagram:**

```
Waterfall:    Spec ──────→ Code ──────→ Done
              (frozen)     (pray)

SDD:          Spec ←──→ Code ←──→ Spec ←──→ Code
              (evolves)   (informed)  (updated)
```

Specs and code evolve together through feedback loops.

---

## Slide 13 — SDD vs TDD vs BDD

| Approach | Spec Source | Written When | AI-Friendly? |
|----------|------------|-------------|-------------|
| No specs | Chat history | Never | Poor |
| TDD | Test cases | Before code | Partial |
| BDD | User stories | Before tests | Partial |
| **SDD** | **Formal specs** | **Before everything** | **Designed for it** |

SDD is the first approach built *for* the AI era.

---

## Slide 14 — Why Write Things Down?

> "If you're thinking without writing, you only think you're thinking."
>
> — Leslie Lamport, *Specifying Systems*, 2002

Large quote, centered.
The act of writing specs forces clarity.
