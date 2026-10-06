# Section 8: Advanced Features

## Slide 35 — Stores: Cross-Repo Planning

**One Plan. Many Repos.**

```
+------------------+
|   Store (repo)   |
|   Shared Specs   |
+--------+---------+
         |
    +----+----+----+
    |         |    |
    v         v    v
 Repo A    Repo B  Repo C
 (API)     (Web)   (Mobile)
```

Platform teams publish specs.
Product teams consume them.

---

## Slide 36 — 36+ Supported Tools

**Works with your existing setup.**

Claude Code · GitHub Copilot · Cursor · Amazon Q ·
Codeium · Windsurf · Aider · Continue · Zed ·
JetBrains AI · VS Code · and more...

No vendor lock-in. MIT licensed.

---

## Slide 37 — Brownfield Ready

**You don't need to start from scratch.**

```bash
cd your-existing-project
openspec init
```

Two commands. Your existing code stays untouched.
Specs describe what you build NEXT, not what already exists.

---

## Slide 38 — Keeping AI in Sync

**`openspec update`**

- Refreshes AI instruction files in your project
- Run after updating OpenSpec or changing config
- Ensures every AI tool reads the latest specs and rules

```bash
openspec update
```

Your AI assistants are only as good as their instructions.
