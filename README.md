# Gemini CLI — Starter Boilerplate

> Ready-to-use `GEMINI.md` and `.gemini/settings.json` for your project. Clone, copy, edit.

Part of [agent-anatomy](https://github.com/agent-anatomy) — boilerplates for every AI coding agent.

📊 **[View diagram →](https://agent-anatomy.github.io/graphics/gemini.html)**

---

## Usage

```bash
git clone https://github.com/agent-anatomy/gemini.git .gemini-boilerplate
cp .gemini-boilerplate/GEMINI.md ./GEMINI.md
cp -r .gemini-boilerplate/.gemini ./.gemini
rm -rf .gemini-boilerplate
```

Then edit `GEMINI.md` to match your project.

---

## What's included

```
GEMINI.md                          ← project instructions, always read
.gemini/
└── settings.json                  ← Gemini CLI configuration
```

---

## What is GEMINI.md?

`GEMINI.md` is the project instruction file for Gemini CLI (Google's AI coding agent). Gemini reads it automatically at the start of every session — no configuration needed.

Equivalent to `CLAUDE.md` for Claude Code, or `AGENTS.md` for Codex.

**What to put in GEMINI.md:**
- Project description and stack
- Build, test, and lint commands
- Coding conventions
- What Gemini should never touch
- Architecture context

---

## Hierarchical GEMINI.md

Like Claude Code, Gemini CLI supports `GEMINI.md` in subdirectories. Root file always loads. Subdirectory files load when Gemini works in that subtree.

Use for monorepos where different packages have different conventions.

---

## What to commit vs gitignore

| File | Commit? |
|------|---------|
| `GEMINI.md` | ✅ Yes |
| `.gemini/settings.json` | ✅ Yes |

---

## FAQ

**Does Gemini read GEMINI.md automatically?**
Yes. Every session, no setup required.

**Can I have GEMINI.md in subdirectories?**
Yes. Gemini merges root + subdirectory instructions when working in that subtree.

**What goes in .gemini/settings.json?**
Gemini CLI configuration — auth type, theme, and other preferences.

**Is GEMINI.md the same concept as CLAUDE.md?**
Yes. Both are session instruction files committed to git so the whole team benefits. Different agent, same idea.

---

## Other agents

| Agent | Boilerplate |
|-------|-------------|
| Claude Code | [agent-anatomy/claude](https://github.com/agent-anatomy/claude) |
| Cursor | [agent-anatomy/cursor](https://github.com/agent-anatomy/cursor) |
| OpenAI Codex | [agent-anatomy/codex](https://github.com/agent-anatomy/codex) |
| Windsurf | [agent-anatomy/windsurf](https://github.com/agent-anatomy/windsurf) |
| GitHub Copilot | [agent-anatomy/copilot](https://github.com/agent-anatomy/copilot) |
| Aider | [agent-anatomy/aider](https://github.com/agent-anatomy/aider) |
