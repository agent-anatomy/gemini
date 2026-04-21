# Gemini CLI — Starter Boilerplate

> Ready-to-use `GEMINI.md` and `.gemini/settings.json` for your project. Clone, copy, edit.

Part of [agent-anatomy](https://github.com/agent-anatomy) — boilerplates for every AI coding agent.

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

## What to commit vs gitignore

| File | Commit? |
|------|---------|
| `GEMINI.md` | ✅ Yes |
| `.gemini/settings.json` | ✅ Yes |

---

## Other agents

| Agent | Boilerplate |
|-------|-------------|
| Claude Code | [agent-anatomy/claude](https://github.com/agent-anatomy/claude) |
| Cursor | [agent-anatomy/cursor](https://github.com/agent-anatomy/cursor) |
| OpenAI Codex | [agent-anatomy/codex](https://github.com/agent-anatomy/codex) |
| More... | [agent-anatomy](https://github.com/agent-anatomy) |
