# AGENTS.md — .github

**Public.** This repository holds the organisation profile shown on github.com/Volve-Vision
(`profile/README.md`) and its diagrams.

Keep it short and factual. It is read by investors and partners, so the rules of
`Volve-Vision/updates-playbook` apply here too: no stack detail, no internal hostnames, no metrics
beyond catalogue scale, and nothing about release status that is not true in the stores today.

Diagrams are generated from the templates in `updates-playbook/diagram-templates/` and shipped as a
light and a dark file referenced through `<picture>`.

## Organisation rules

- Map of every repository, its checkout and its deploy target: **`Volve-Vision/volve-handbook`**.
- If you create, rename, transfer or archive a repository, run `~/Volve/bin/volve-repo-map` and
  commit the handbook **in the same session**. The map is generated, never hand-edited.
- Remotes are `https://VolveVision@github.com/Volve-Vision/<repo>.git`; `gh` picks the account
  automatically through `~/Volve/bin/gh`.
- Never deploy, restart a service or touch production data without the owner asking in this session.
