# Zotero MCP Codex Update Channel

This public repository contains only compiled update artifacts for the private
`zotero-mcp-codex` maintenance fork. It does not contain the project source or
configuration secrets.

- `updates.json` is the Zotero update manifest.
- `releases/v<version>/zotero-mcp-plugin.xpi` is an immutable release artifact.
- `releases/v<version>/SHA256SUMS` records the artifact checksum.

Artifacts are built from a version tag in the private canonical repository and
published by GitHub Actions through a repository-scoped deploy key. Do not edit
the update manifest or release directories manually.
