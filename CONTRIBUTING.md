# Contributing to the AI-Human Covenant Starter Kit

Thank you for helping build a global, open, *actionable* standard for responsible AI.  
This project welcomes contributions from developers, designers, educators, operators, researchers, and policy folks.

## 🧭 Principles
We model the Covenant: dignity, transparency, care, justice, creativity.  
Be kind. Assume good intent. Credit generously. Cite sources.

## 🧰 What You Can Contribute
- **Templates** (policies, checklists, disclosures)
- **Guides** (for devs, orgs, educators, communities)
- **Examples** (case studies, how-to’s, sample implementations)
- **Assets** (posters, share cards, diagrams)
- **Translations** (any file → new language folder)
- **Fixes** (typos, clarity, structure, links)

## 🗂 Repo Layout (simplified)
assets/ # visuals & shareables
docs/ # guides & how-tos
examples/ # reference implementations, case studies
templates/ # copy-and-paste starters (policies, forms)
zine/ # culture & storytelling
index.json # machine-readable index of kit items
manifest.yml # human-friendly manifest of kit items

## ✅ Quick Contribution Flow
1. **Fork** the repo and create a branch:
   - `feat/<short-name>` (new content)
   - `fix/<short-name>` (edits)
   - `i18n/<lang>-<file>` (translations)
2. **Add your content** in the right folder.
3. **Update** `index.json` and `manifest.yml` with your new item(s).
4. **Test links** (relative links) and run a quick spell/format pass.
5. **Open a Pull Request** with:
   - A clear title (e.g., “feat: add AI Incident Response Plan”)
   - A short **rationale** (what/why)
   - Any **sources** or prior art

> For substantial changes to core concepts, open an **Issue** first to discuss.

## 🔎 Content Standards
- **Plain language.** Jargon only when necessary (define it).
- **Actionable.** Checklists, steps, examples beat abstractions.
- **Attribution.** Credit inspirations and cite sources.
- **Neutral & global.** Applicable across cultures and org sizes.
- **Licensing.** Text under **CC BY-SA 4.0**; code under **MIT**.  
  Add SPDX headers when appropriate:
  - Markdown: `<!-- SPDX-License-Identifier: CC-BY-SA-4.0 -->`
  - Code: `// SPDX-License-Identifier: MIT`

## 🌐 Translations
Create: `TRANSLATIONS/<lang>/<path-to-file>`  
Example: `TRANSLATIONS/es/templates/ai_policy.md`  
Add translator credits at the top and update `manifest.yml` (add `languages:` list).

## 🏷 Labels We Use
- `good-first-issue`, `help-wanted`
- `templates`, `docs`, `examples`, `design`, `i18n`
- `governance`, `policy`, `safety`, `privacy`

## 🔁 Reviews & Merging
- 1 reviewer for small fixes; 2+ for new frameworks/templates.
- Maintain consistent tone and structure.
- Maintainers may suggest edits for clarity, neutrality, or scope fit.

## 🔒 Ethics & Scope
We do **not** accept content that promotes harm, surveillance abuse, discrimination, or deceptive practices.

## 🙌 Credits
Please add yourself to the PR description for credits. We periodically update acknowledgements.

