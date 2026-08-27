# How to contribute

Your half-finished gem, your hacky automation, your "I'm not sure this is good enough" prototype — it's worth sharing. A tool with a two-line description is better than a tool nobody knows about.

Nothing here is officially endorsed or approved. Everything is shared as-is: things people have tried, things that worked, things worth adapting. Add yours.

---

## Quick path: open an issue

If you'd rather not touch git, just [open a new project issue](../../issues/new?template=new-project.yml) and fill in the form. Someone will add it for you.

---

## Standard path: add it yourself

### 1. Fork and clone this repo

```bash
git clone https://github.com/YOUR-USERNAME/design-ai-toolkit.git
cd design-ai-toolkit
```

### 2. Copy the project template

```bash
cp -r _template projects/your-project-name
```

Use a short, lowercase, hyphenated name (e.g. `ux-writing-bot`, `cli-review-skill`).

### 3. Fill in your project page

Open `projects/your-project-name/README.md` and fill in the sections. Only three are required: **What it does**, **How to use it**, and **Status**. The rest are optional.

**Not sure what to write?** You can paste the template into an LLM and ask it to help you fill it in based on a description of your tool. The template is designed to work well with this workflow.

### 4. Add your project to the landing page

Open `README.md` in the repo root and add a row to the table that matches your project type (Gem, Skill, Code, or Other). **This step is required** — it's how people find your tool.

Match this format:

```markdown
| [Your project name](projects/your-project-name) | Your Name | Use case | ☁️ API name / 💻 Local | One-line description |
```

### 5. Open a pull request

```bash
git checkout -b add/your-project-name
git add .
git commit -m "Add your-project-name"
git push origin add/your-project-name
```

Then open a PR. No review gatekeeping — we'll merge it quickly.

---

## What counts as a contribution?

Anything that helps designers work with AI. It doesn't have to be polished, public, or complete.

| Contribution | Effort | Example |
|-------------|--------|---------|
| A Gemini gem | 🟢 Low | A gem configured for a specific writing task |
| A Copilot skill | 🟢 Low | A `.md` skill file with a good system prompt |
| A link + description | 🟢 Low | "Here's a Figma plugin I found useful" |
| A prototype | 🟡 Medium | A working proof-of-concept |
| A full tool | 🔴 Higher | A complete, documented, installable tool |

All levels are welcome. A gem with a two-line description is better than a gem nobody knows about.

---

## Updating an existing project

Just edit the files in `projects/your-project-name/` and open a PR. No need to re-do the template.

---

## Questions?

Open an issue or ask in the team channel. We'd rather help you contribute than have your tool stay hidden.
