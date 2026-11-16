# Copilot Studio skill upload packages

Compliant with:
- `SKILL.md` quoted YAML `name` + `description`
- Path depth <= 3
- No `*.mcs.yml`
- **No `.json` files** (converted to `.txt` — Copilot Studio rejects `.json` as skill script files)
- Scripts: `.py .js .mjs .cjs .ts .mts .sh .bash` only

Upload via **Build > Skills > Upload skill**. Use the zip from this folder (not Downloads).
