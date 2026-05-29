# Repository Instructions

This repository maintains an Awesome list in `README.md`. When editing or regenerating the README, follow the official Awesome-list guidelines and the local conventions below.

## README Rules

- Keep the first section as `## Contents`; do not add `Contributing` or footnote sections to the table of contents.
- Preserve the existing title, Awesome badge, logo, and short description at the top of `README.md` unless the user asks to change them.
- Use one blank line before and after each `##` heading.
- Use one bullet per entry with this format: `- [Name](https://example.com) - Description.`
- Do not include GitHub star badges or other per-entry badges in `README.md`.
- Do not include dates in entries, including month/year, day/month/year, year-only, or conference/year parentheticals.
- Do not include empty links such as `[](https://example.com)`.
- Ensure each description starts with an uppercase character and ends with a period.
- Avoid descriptions that repeat the item name at the start.
- Keep section entries alphabetized by link title unless the user explicitly asks for another order.
- Preserve product-name spacing and casing, especially `.NET`, `GitHub`, `Power BI`, `Azure AI Foundry`, and `Microsoft 365`.

## Sync Workflow

- Treat `README.md` as the published Awesome list and `temp.md` as a working catalog/source file.
- When syncing from `temp.md` to `README.md`, copy useful entries and descriptions but strip entry dates, GitHub star badges, empty links, and scratch comments from `README.md`.
- When syncing descriptions from `README.md` back to `temp.md`, update only the description text and preserve `temp.md` metadata such as dates, GitHub star badges, empty links, and draft-only comments unless the user explicitly asks to remove them.
- Match entries by URL when doing automated syncs; do not rely on line numbers or section order alone.
- After mechanical date or badge removal, scan for spacing artifacts such as `for.NET`, `using.NET`, `Official.NET`, or `with.NET`, and fix them to include the space before `.NET`.

## Verification

- Run `npm run lint:awesome` after README changes.
- Check alphabetical order for the curated sections before finishing.
- Search `README.md` for leftover `github stars`, empty links, date parentheticals, and glued `##` headings before finishing.
- If Python is unavailable on Windows, use an equivalent Node.js check instead of the local Python checker.
- Do not modify unrelated files such as `.gitignore` while cleaning the README.
