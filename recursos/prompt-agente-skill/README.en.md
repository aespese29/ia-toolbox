# 🧭 Prompt, Agent or Skill? — Decide and generate the artifact

[Spanish](README.md) · [English](README.en.md)

An interactive tool that settles the recurring question: should this be a **prompt**, an **agent** or a **Skill**? Answer three questions, pick an approach, and the tool **generates the artifact ready to paste into Copilot**.

## 🚀 Get started

👉 **[Open the resource](https://aespese29.github.io/ia-toolbox/recursos/prompt-agente-skill/)**

## 🧩 What it asks for and what you get

| If you choose | It asks for | You get |
|---|---|---|
| 💬 **Prompt** | Role, task, context, output format and constraints | A structured prompt for Copilot Chat |
| 🤖 **Agent** | Purpose, responsibilities, knowledge, boundaries and skills | The agent instructions in Markdown plus the natural-language prompt for Agent Builder |
| 📦 **Skill** | `name`, `description`, steps, rules and output format | A valid `SKILL.md` with its frontmatter and the folder tree |

Everything you generate can be **copied to the clipboard** or **downloaded as Markdown**.

## 🤔 The three questions

1. **Will you do it only once?** → Prompt
2. **Does it repeat and must always come out the same?** → Skill
3. **Is it a role with several tasks, its own knowledge and an audience?** → Agent + Skills

> Rule of thumb: one new agent per responsibility; one skill per task within that responsibility.

## 📐 The mandatory structure of a Skill

The tool follows and enforces the minimum anatomy:

```text
kit-anuncio-evento/
  ├─ SKILL.md                    ← required
  ├─ references/guia-estilo.md     (optional)
  └─ templates/plantilla-kit.md    (optional)
```

`SKILL.md` **always** starts with YAML frontmatter between `---` and two required fields:

- **`name`** — lowercase, kebab-case (the tool normalises it for you).
- **`description`** — this is what decides **when the skill is triggered**. State when to use it and when **not** to.

## 🔗 Related resources

- 🧩 [SKILL.md template in 6 blocks](../plantilla-skill-md/) — the conceptual guide behind this generator.
- 🎓 [Session: How Skills turn Copilot into a real teammate](../../sessions/skills-copilot-companero-de-trabajo/) — the full talk, with the demo kit.

## 🛠️ Technical notes

- A **single HTML file**, with no dependencies and no backend. Download it and it works offline.
- The logo is embedded as base64; the typefaces (Manrope and Inter) load from Google Fonts, falling back to Arial.
- The data you type **never leaves your browser**: no analytics, nothing sent to any server.

---

**Adrián Espés** · Microsoft MVP · Microsoft 365 Copilot · [adrianespes.com](https://adrianespes.com)
