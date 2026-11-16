# Copilot Studio skill upload packages

Compliant with:
- `SKILL.md` with quoted YAML `name` + `description`
- Max path depth **3** (`skill/folder/file`)
- No `*.mcs.yml` sidecars
- File types per [Microsoft skill allowlist](https://learn.microsoft.com/en-us/microsoft-365/copilot/extensibility/declarative-agent-skills):
  - Scripts: `.py .js .mjs .cjs .ts .mts .sh .bash` only (no `.json` under `scripts/`)
  - Resources: `.md .json .html .txt …` (`.css .svg .twx` excluded or converted)

Upload via **Build > Skills > Upload skill**.
