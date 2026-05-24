# CLAUDE.md

## Repository Overview

**first-steps** is a Python learning/study repository ("estudio python"). It is in its earliest stage — currently just a README — and is intended to grow as a hands-on Python practice environment.

- **Owner:** Sertorio62
- **Language:** Python
- **Purpose:** Beginner-to-intermediate Python exercises, scripts, and experiments
- **Status:** Initial scaffolding; no source files yet

---

## Repository Structure (expected as it grows)

```
first-steps/
├── README.md          # Project overview
├── CLAUDE.md          # This file
├── exercises/         # Python exercises organized by topic
├── scripts/           # Standalone Python scripts
└── notes/             # Markdown notes or Jupyter notebooks
```

There is no enforced structure yet. When adding new files, use clear, descriptive names and keep related content grouped in subdirectories.

---

## Development Conventions

### Python Style
- Follow [PEP 8](https://peps.python.org/pep-0008/) for all Python code.
- Use 4-space indentation (no tabs).
- Keep lines under 88 characters (compatible with `black` if added later).
- Use descriptive variable and function names in English.

### File Naming
- Python files: `snake_case.py`
- Directories: `snake_case/` or short lowercase names

### Comments
- Write comments only when the intent is non-obvious.
- Prefer clear code over heavy commenting.

### Commits
- Use short, imperative commit messages (e.g., `add fibonacci exercise`, `fix loop in sorting script`).
- Commit working code; avoid committing broken scripts unless clearly marked `WIP:`.

---

## Working with This Repository

### Running Python files
```bash
python3 <filename>.py
```

### No build system or test framework is configured yet.
If tests are added later, update this section with the test runner and commands.

---

## AI Assistant Guidelines

- This is a learning repository. Prefer **clear, readable code** over clever one-liners.
- When writing exercises or examples, add a brief docstring explaining what the code demonstrates.
- Do not introduce third-party dependencies without noting them in the README.
- Keep examples self-contained where possible — avoid cross-file dependencies unless teaching modules/imports.
- When the user asks for explanations, prioritize pedagogical clarity over brevity.
- Development branch convention: feature branches follow `claude/<description>` naming.

---

## Git Workflow

- Default branch: `main`
- Feature/AI branches: `claude/<short-description>`
- Push changes to the designated branch and do **not** force-push to `main`.
