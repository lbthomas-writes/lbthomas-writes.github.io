# Project Guidelines for LB Thomas Writes (Website)

## Quick-start checklist

- Always read this file and `README.md` before making changes.

- Prefer small, focused edits over large refactors.

- When unsure about requirements, ask for clarification.

## Local development commands

| Task              | Command          |
| ----------------- | ---------------- |
| Preview Hugo site | `hugo server -D` |
| Build Hugo site   | `hugo`           |

## GitHub Pages Deployment Setup

To make the site go live, you must configure the following in the GitHub repository settings:

1.  **Source**: Go to **Settings** > **Pages**. Under **Build and deployment** > **Source**, select **GitHub Actions** from the dropdown menu.
2.  **Visibility**: Ensure the repository is **Public** (Settings > General > Danger Zone). GitHub Pages is only free for public repositories on standard accounts.
3.  **Custom Domain (Optional)**: If you use a custom domain, add it in the Pages settings; otherwise, it will be served at `https://lbthomas-writes.github.io/`.

## Content and writing conventions

- Use the PaperMod theme styles; avoid custom CSS unless necessary.

- Website content is for an author's blog about the book.

- Scrivener exports, wiki, and novel writing notes are maintained in the separate `founders-legacy` repository.

## Non-goals

- Do not change the Hugo theme without discussion.

Other novel-related content (wiki, scrivener) is in the `founders-legacy` repo.
