# AGENTS.md - Developer & AI Agent Guide for skills-write-javascript-actions 🤖

## 🎯 Repository Overview
**skills-write-javascript-actions**: Include a 1280×640 image, course name in sentence case, and a concise description in emphasis. In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.

---

## 🏗️ Repository Architecture
Key directories and entrypoints: `.github/, LICENSE, README.md`.

### Tech Stack & Runtime
- **Category:** GitHub Learning Lab / Skills Course Module
- **Format:** Markdown (`.md`), HTML, and GitHub Actions workflows

## ⚙️ Verification Instructions
- Ensure Markdown formatting conforms to CommonMark and GitHub Flavored Markdown.
- Validate GitHub Actions syntax in `.github/workflows/` if present.

---

## 🛡️ Coding & Safety Guidelines for Autonomous Agents

1. **Documentation Integrity:** Preserve all existing docstrings, header comments, and licensing banners. Never delete context unless specifically instructed.
2. **Zero Hardcoded Secrets:** Never embed API keys, OAuth tokens, personal access tokens, or sensitive credentials in committed files. Read credentials exclusively from environment variables or secure credential paths.
3. **Git Hygiene:**
   - Do not force-push (`git push --force`) or execute destructive resets.
   - Never modify root git configurations or harness infrastructure outside task scope.
   - Keep git diffs atomic, focused, and verified before committing.
4. **Agent Workflow Protocol:**
   - **Plan:** Inspect codebase architecture and dependencies before editing.
   - **Act:** Make minimal, clean, high-precision changes.
   - **Verify:** Run the appropriate verification commands listed above.
   - **Reflect:** Confirm zero regressions and review `git diff`.

---
*Maintained by Ayyappa Pravin • Built for Antigravity, Claude, Cursor & Autonomous AI Agents.*
