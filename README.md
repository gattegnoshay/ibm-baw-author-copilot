# IBM BAW Author

Modern **Microsoft Copilot harness** agent package (no topics).

Per [Microsoft Learn – Copilot harness](https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/overview) and [Skills overview](https://learn.microsoft.com/en-us/microsoft-copilot-studio/agents-experience/skills-overview):

| Component | Location |
|-----------|----------|
| Instructions | `settings.mcs.yml` |
| Skills | `behaviors/<skill>/SKILL.md` (+ `skill.mcs.yml`) |
| Knowledge | `capabilities/knowledge/` |
| Tools | add connectors/MCP in Copilot Studio as needed |

Topics are **not** used. Skills replace topic flows for the Microsoft Copilot harness.

## GitHub Copilot

The same skill packs are also under `.github/skills/` for GitHub Copilot agent skill discovery.

## Import

1. Create a **Microsoft Copilot harness** agent in Copilot Studio (not classic/standard topics agent).
2. Upload each folder under `behaviors/` as a skill package, **or** sync via Copilot Studio VS Code / CLI (`template: cliagent-`).
3. Paste/adapt instructions from `settings.mcs.yml`.

Source skills: [ibmbpm/ibm-baw-skills-and-bob-modes](https://github.com/ibmbpm/ibm-baw-skills-and-bob-modes) (Apache-2.0)
