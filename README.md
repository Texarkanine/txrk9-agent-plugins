# txrk9-agent-plugins

Curated **Cursor** and **Claude Code** marketplace catalogs listing agent plugins maintained by Texarkanine.

## Contents

| Catalog | Path | Use |
|--------|------|-----|
| Cursor | [`.cursor-plugin/marketplace.json`](.cursor-plugin/marketplace.json) | Add this marketplace in Cursor, then browse/install listed plugins. |
| Claude Code | [`.claude-plugin/marketplace.json`](.claude-plugin/marketplace.json) | Register this marketplace in Claude Code, then install plugins from it. |

## Plugins

### [SLOBAC](https://github.com/Texarkanine/slobac) (`slobac`)

Test-suite audit for mature codebases: orchestrates read-only assessment of a target test directory against the [SLOBAC manifesto](https://texarkanine.github.io/slobac/), producing a markdown report of smells (taxonomy-defined slugs), behavior summaries, and prescribed fixes. Ships multiple skills (`audit`, `scout`, `batch`, `cross-suite`); invoke e.g. `/slobac:audit` after install.

## Adding this marketplace

Clone or reference this repository and point your harness at the JSON file above, or subscribe by GitHub URL if your client supports remote marketplace URLs (follow Cursor / Anthropic docs for the current UI).
