# Author / design-time

This repository packages IBM BAW **GitHub Copilot agent skills** (Agent Skills standard).

## How Copilot uses this repo

Skills live under `.github/skills/<skill-name>/SKILL.md`. Copilot discovers and loads them automatically when relevant — do **not** treat this repo as a website knowledge link only.

When asked to help with IBM Business Automation Workflow (Author / design-time) tasks, prefer the matching skill under `.github/skills/`.

## Installed skills

- `generate-baw-bpmn`
- `generate-baw-business-objects`
- `create-baw-portal`
- `create-baw-widget`
- `create-baw-external-task-ui`
- `generate-baw-tests`
- `test-baw-service-flows`
- `review-baw-code`
- `process-compliance-violation-detection`
- `baw-project-doc`
- `baw-dependency-mapper`
- `baw-toolkit-analyzer`
- `baw-endpoint-validation`
- `baw-export-import-helper`
- `audit-baw-readiness`
- `compare-baw-versions`

## Optional: Copilot Studio YAML

Legacy Copilot Studio MCS YAML (topics/settings) is under `copilot-studio/` for import into Microsoft Copilot Studio. Primary capability is the `.github/skills` pack.

Source: https://github.com/ibmbpm/ibm-baw-skills-and-bob-modes (Apache-2.0)
