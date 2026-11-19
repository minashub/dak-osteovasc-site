# Agent rules

Claude is the master agent for the DAK repositories. Codex, Gemini, Copilot and every other agent
follow these rules here.

## Naming spec v1 (2026-11-19)

File, folder, index and cloud names follow `rules/naming-spec-dev.md` in `minashub/dak-science`.

- Every new file ends with a domain suffix: `bve`, `mito`, `marrow`, `osteo`, `biomat`, `img`,
  `dev`, or `global` (cross-domain governance and index notes only). `immuno` is not a suffix.
- Python and shell files use `snake_case_<suffix>.py` / `.sh`. Other files use
  `kebab-case-<suffix>.<ext>`. A YAML `domain_suffix` must match the name.
- Tool-defined names stay as they are: `README.md`, `AGENTS.md`, `index.html`, `CNAME`.
  Existing published paths stay as they are, because renaming them breaks links.
- Never assign `bve` as a default suffix.
- Text is formal English and ASCII only, with no emoji. Status markers are `[PASS]`, `[FAIL]`,
  `[WARN]`, `[SYNC]`.
