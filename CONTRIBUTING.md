# Contributing to the BA Toolbox

Thank you for helping improve the BA Toolbox! Contributions of all kinds are welcome — fixing a typo, improving an explanation, adding a new method or example, or suggesting a new section.

There are two ways to contribute depending on your comfort with Git.

---

## Option 1 — No Git knowledge required (GitHub web editor)

You only need a free GitHub account.

1. **Open the file you want to change** — navigate to the file in the repository on GitHub.com.
2. **Click the pencil icon** (✏️) in the top-right corner of the file view. This opens the file in GitHub's built-in editor.
3. **Make your changes** directly in the editor.
4. **Scroll to the bottom** to the "Propose changes" section.
5. **Write a short description** of what you changed and why (e.g. *"Fixed typo in Phase 3 section"* or *"Added Cynefin to Methods Matrix"*).
6. **Click "Propose changes"** — GitHub will automatically create a fork and a branch for you.
7. On the next screen, click **"Create pull request"** to submit your change for review.

A maintainer will review your suggestion and merge it or leave feedback.

> **Tip:** To suggest a completely new file or section, open an [Issue](../../issues) instead and describe what you'd like to add. A maintainer or another contributor can help create it.

---

## Option 2 — Standard Git workflow (for git-familiar users)

1. **Fork** the repository by clicking "Fork" in the top-right of the GitHub page.
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/<your-username>/BA_toolbox.git
   cd BA_toolbox
   ```
3. **Create a branch** for your change:
   ```bash
   git checkout -b my-improvement
   ```
4. **Make your changes** — edit or add Markdown files as needed.
5. **Commit** your work with a clear message:
   ```bash
   git add .
   git commit -m "Add Cynefin framework to BA Methods Matrix"
   ```
6. **Push** to your fork:
   ```bash
   git push origin my-improvement
   ```
7. **Open a Pull Request** on GitHub from your branch to `main` in this repository.

A maintainer will review your PR and may leave comments or merge it.

---

## Contribution Guidelines

- **Keep it practical** — this is a reference for working BAs, not an academic text. Prefer clear, actionable language.
- **Match the existing style** — look at the surrounding content for tone, formatting, and table structure before adding new material.
- **One change per PR** — small, focused pull requests are easier to review and merge quickly.
- **Update the relevant index** — if you add a new file or section, update the Contents table in [`README.md`](README.md).
- **No jargon without explanation** — if you introduce a new acronym or framework name, add a brief definition.

---

## Reporting Issues or Suggestions

Not ready to edit files directly? Open an [Issue](../../issues) to:
- Report a mistake or outdated information
- Suggest a new method, deliverable, or example
- Ask a question about how to use the toolbox

Issues are just as valuable as pull requests — they help maintainers understand what the community needs.
