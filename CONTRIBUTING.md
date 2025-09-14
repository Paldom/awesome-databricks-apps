# Contributing to Awesome Databricks Apps

Thank you for your interest in contributing to Awesome Databricks Apps! This guide will help you understand how to contribute effectively to this curated list.

Here’s a drop‑in **CONTRIBUTING.md** tailored for this repository.

---

## TL;DR (fast checklist)

* ✅ **One link per PR.** Keep changes focused and easy to review.
* ✅ **Scope:** Only add items that directly help people **build, run, or operate Databricks Apps** (apps that run on the Databricks platform).
* ✅ **Place it in the most specific section** (see section map below).
* ✅ **Use the standard entry format** and **one‑sentence description**:
  `- [Name](URL) - Sentence starts with a capital and ends with a period.`
* ✅ **No duplicates.** Search the list first.
* ✅ **Sort alphabetically within a subsection** unless the subsection explicitly mirrors upstream “official” ordering.
* ✅ **Use canonical URLs** (no tracking params; prefer the project’s GitHub repo when appropriate).
* ✅ **Run the linter locally:** `npx awesome-lint` and fix all findings before opening your PR. 
* ✅ **PR title:** `Add: ProjectName`.
* ✅ By contributing, you agree your contribution is released under **CC0‑1.0** (public domain). 

---

## What belongs here (acceptance criteria)

An item is in‑scope if it directly supports **Databricks Apps** developers or operators:

* **Official Docs, Templates & Samples:** Canonical documentation or templates from Databricks.
* **Products Hosted on Databricks:** Full apps/tools that are actually deployed as **Databricks Apps** (prefer open source repos).
* **Demo Apps / Starters / Solution Accelerators:** Minimal or focused examples that demonstrate Databricks Apps features (auth, OBO, data access, Genie, MLflow, Lakehouse access, etc.).
* **Tooling/SDKs/CLIs/Libraries:** Client tools that materially improve developing, deploying, or operating Databricks Apps.
* **Tutorials/Guides/Use cases/Blogs:** Learning resources that show *how to* build/operate Databricks Apps end‑to‑end (not generic Databricks content).

> Tip: Databricks Apps are first‑class apps you deploy *on* the Databricks platform (not just code that uses Databricks APIs). Keep submissions focused on this modality. 

### Out of scope

* Generic data/AI articles that don’t meaningfully involve **Databricks Apps**.
* Closed, marketing‑only pages without a repo or substantive build/run instructions.
* Dead/unmaintained projects without a working demo/readme.
* Duplicates of items already in the list.
* Content that’s primarily about a different product/platform.

---

## Where should my item go?

Use the **most specific** section. If it fits multiple, pick the one that best matches *why* someone would use it.

* **Official Docs & Product Overview** → Official product pages & docs.
* **Official Templates & Samples** → Databricks‑maintained templates/samples. Keep the upstream order for the per‑framework “official” subsections.
* **Products Hosted on Databricks** → Full apps running as Databricks Apps.
* **Demo Apps** → Self‑contained demos of capabilities.
* **Starter Repositories** → Boilerplates that scaffold Databricks Apps.
* **Solution Accelerators** → Industry/use‑case focused kits.
* **Resources** → Documentation, related services (e.g., Unity Catalog, MLflow), tooling/SDKs/CLI, tutorials, use cases, blogs, community.

If you believe a **new subsection** is warranted, propose it in the PR description and include at least **3–5 strong items** to justify the new category.

---

## Entry format & style

Use exactly this bullet style:

```md
- [Project Name](https://example.com) - One concise sentence that starts with a capital letter and ends with a period.
```

**Rules**

* **Sentence case & period:** Start with a capital letter, end with a period. The linter checks this. 
* **Keep it concise:** One sentence. Avoid marketing, superlatives, and emojis. Explain *what it is/does* and *why it’s useful*.
* **Canonical links:** Prefer the project homepage or GitHub repo. Remove tracking parameters.
* **Ordering:** Alphabetical within a subsection (except where noted above for “Official” upstream lists).
* **One link per item:** If you must include alternates (docs/demo), link the primary and mention others succinctly in the description only when necessary.

**Good**

```md
- [FastAPI Starter](https://github.com/Paldom/databricks-apps-fastapi-starter) - Boilerplate that scaffolds a FastAPI-based Databricks App with local dev and bundle deploy flows.
```

**Not good**

```md
- [Cool Starter!!!](https://example.com?utm=promo) - The best starter ever 🔥🔥🔥 for any cloud.
```

---

## How to contribute

1. **Fork** the repo and create a branch:
   `git checkout -b add-projectname`
2. **Edit `README.md`** and add your item in the correct section.
3. **Sort the subsection alphabetically** (unless it’s an “Official” ordered block).
4. **Run the linter** locally and fix all findings:

   ```bash
   npx awesome-lint
   ```

   * The linter enforces Awesome‑style rules (badge, list marker style, trailing slash, **no dead URLs**, item formatting, etc.). You can temporarily disable a specific rule using special comments if truly necessary (see examples in the linter docs). 

   `git commit -m "Add: ProjectName"`
6. **Open a PR** with **one link only** and include:

   * Why this is valuable for **Databricks Apps** users.
   * Which section you chose and why.
   * Any caveats (e.g., alpha status).
7. (Nice‑to‑have) Review another open PR and leave actionable feedback.

> CI runs `awesome-lint` on PRs (via GitHub Actions). Submissions must pass before merge. 

---

## Quality bar (what maintainers look for)

* **Relevance:** It’s clearly about **Databricks Apps** (building, deploying, or operating apps on Databricks). 
* **Clarity:** A solid README with setup/run instructions; ideally a screenshot/GIF.
* **Health:** The repo looks maintained (recent commits/issues/releases).
* **Neutrality:** Minimal marketing; focus on facts and utility.
* **Curation:** Ask “is it *awesome*?” Curate, don’t collect. It’s fine to leave mediocre items out. 

We may edit wording for brevity/consistency, move the item to a better section, or close the PR if it’s out of scope.

---

## Code of Conduct

Be kind, constructive, and inclusive.

---

## Updating Existing Entries

If you find an outdated link or description:
1. Open an issue first to discuss the change
2. Follow the same PR process for updates
3. Explain why the update is needed

## Removing Entries

Items may be removed if they:
- Become unmaintained (no updates in 2+ years)
- Have broken links that can't be fixed
- No longer relate to Databricks Apps
- Violate our guidelines

To suggest removal, open an issue with your reasoning.

## Recognition

All contributors are valued! Your contributions help the Databricks Apps community discover valuable resources and ship better Databricks Apps. ✨


