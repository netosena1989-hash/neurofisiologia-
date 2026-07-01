# AGENTS instructions for neurofisiologia-

## Display language
- Default the user-facing display language to Brazilian Portuguese (pt-BR).
- Keep the document language metadata consistent with the app content; preserve or update the `lang` attribute in [index.html](index.html) to match the selected locale.
- Prefer Portuguese labels, button text, helper text, and documentation unless the user explicitly requests another language.

## Project conventions
- This repository is a small static web app using plain HTML, CSS, and JavaScript.
- Main editable files are [index.html](index.html), [style.css](style.css), and [script.js](script.js).
- There is no build step or package manager workflow in this repo; for local preview, open [index.html](index.html) directly in a browser or serve the folder with a simple static server.

## Guidance for agents
- When adding or updating UI text, keep terminology consistent with the existing Portuguese content.
- Do not introduce untranslated English strings unless required by a library name, API key, or explicit user instruction.
- For broader project context, see [README.md](README.md).
