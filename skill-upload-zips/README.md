# Copilot Studio skill upload packages

**Path depth rule:** Copilot Studio rejects zips with paths nested more than **3 levels** (e.g. `skill/folder/file` is OK; `skill/a/b/c/file` is not).

These zips are flattened accordingly. Large nested template trees (e.g. BaseTWX) are omitted; full sources stay in the GitHub `behaviors/` folders.

Upload via **Build > Skills > Upload skill**.
