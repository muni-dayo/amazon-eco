# AGENTS.md

## Overview

This is a documentation-only repository (`amazon-eco`) containing internal lecture materials for teaching employees how to use Cursor and AI agents. The primary artifact is a Marp slide deck.

## Cursor Cloud specific instructions

### Repository structure

- `marketing/cursor-agent-lecture.marp.md` — Main Marp slide deck (Japanese)
- `marketing/docs/` — Supporting lecture documents
- `marketing/.github/` — Issue/PR templates for the lecture workflow

### Development tools

The only dev tool required is **Marp CLI** (`@marp-team/marp-cli`), installed globally via npm.

### Common commands

| Task | Command |
|------|---------|
| Build slides to HTML | `marp --no-stdin --html marketing/cursor-agent-lecture.marp.md -o marketing/cursor-agent-lecture.html` |
| Start dev server | `cd marketing && marp --no-stdin --html -s -I . --server-port 8080` |
| Build slides to PDF | `marp --no-stdin --html --pdf marketing/cursor-agent-lecture.marp.md -o marketing/cursor-agent-lecture.pdf` |

### Notes

- There are no linting tools, test frameworks, pre-commit hooks, or CI/CD pipelines configured.
- The `--no-stdin` flag is required when running Marp CLI non-interactively (without it, Marp waits for stdin input).
- The server mode flag syntax is `-s -I <dir>` (not `-s <dir>`).
- All content is in Japanese.
- Generated HTML files (e.g. `cursor-agent-lecture.html`) should not be committed — they are build artifacts.
