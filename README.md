# SihyeonJeon

Building small tools for agentic AI workflows: token budgets, tool catalogs,
instruction hygiene, and reproducible evaluation.

## Projects

- [`tool-tax`](https://github.com/SihyeonJeon/tool-tax): measure hidden token
  cost in live MCP servers, OpenAPI files, and agent tool catalogs; diff PR
  changes, generate a slim progressive-loading index, and run a lazy-schema
  MCP stdio proxy. Install:
  `pipx install tool-tax`.
- [`prompt-diet`](https://github.com/SihyeonJeon/prompt-diet): lint agent
  instruction files for prompt bloat, risky wording, and CI-enforceable diet
  labels.
- [`caveman-agent-bench`](https://github.com/SihyeonJeon/caveman-agent-bench):
  benchmark whether compressed primitive instructions preserve agent task
  success.

## Current Focus

- MCP/tool-schema context bloat
- CI budget checks for agent repos
- reproducible agent-tooling claims
- concise OSS docs with visible install and effect
