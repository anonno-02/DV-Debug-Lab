# DV Debug Lab

A practical verification-debug knowledge base for SystemVerilog, UVM, GLS, CDC, X-propagation, assertions, coverage, and regression scripting.

## Local setup

```bash
python -m venv .venv
source .venv/bin/activate     # Linux/macOS
# .venv\Scripts\activate      # Windows PowerShell

pip install -r requirements.txt
mkdocs serve
```

Open the local preview shown by MkDocs, usually:

```text
http://127.0.0.1:8000/
```

## Build static site

```bash
mkdocs build
```

## Deploy to GitHub Pages

```bash
mkdocs gh-deploy
```

Or push to `main` and let the included GitHub Actions workflow deploy it.

## Daily topic publishing flow

1. Create a Markdown topic page under the correct `docs/` category.
2. Add example files under the matching `examples/` folder.
3. Add the topic link to `mkdocs.yml`.
4. Run `mkdocs serve` and check the page.
5. Commit and push.

## Suggested content rule

Every article should solve one real debug pain:

- problem summary
- broken example
- fixed example
- debug flow
- checklist
- common simulator messages
- interview angle
- downloadable example folder
