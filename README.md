# Zotero MCP Codex Update Channel

This is the public automatic-update distribution channel for the independently
maintained Zotero MCP Codex fork. It distributes XPI packages, compiled readable
JavaScript, manifests, checksums and license notices. It does not include the
development TypeScript tree, personal Zotero libraries or configuration secrets.
An XPI is a ZIP archive and its implementation can be inspected after extraction.

- `updates.json`: current Zotero update manifest, pinned to the XPI SHA-256.
- `releases/v<version>/zotero-mcp-plugin.xpi`: immutable versioned package.
- `releases/v<version>/SHA256SUMS`: package checksum.
- `LICENSE`, `NOTICE`, `THIRD_PARTY_LICENSES.txt`: upstream MIT copyright and
  bundled toolkit attribution; these accompany every release directory.

Versions `1.5.1-codex.5` and `.6` predate in-package notices. Their original XPI
bytes and checksums remain unchanged; the complete notices are supplied beside
those packages and at the repository root. New versions include the notices
inside the XPI too. Prefer the latest version from `updates.json`.

Source: [Zotero MCP Guarded](https://github.com/queekye/zotero-mcp-guarded).
The upstream project is [cookjohn/zotero-mcp](https://github.com/cookjohn/zotero-mcp).
This fork is maintained independently and is distributed under MIT; see NOTICE.

The update URL remains
`https://queekye.github.io/zotero-mcp-codex-updates/updates.json`.
Artifacts are built from an exact version tag in the canonical maintenance
repository and published by GitHub Actions using a repository-scoped deploy key.
Do not replace published XPI files: publish a higher version for every correction.
