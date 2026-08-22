# scoop-openehr-explorer

Scoop bucket for [openEHR Explorer](https://github.com/platzhersh/openehr-explorer), a cross-platform desktop app for browsing, querying, and inspecting openEHR CDR instances.

## Install

```powershell
scoop bucket add openehr-explorer https://github.com/platzhersh/scoop-openehr-explorer
scoop install openehr-explorer
```

## Update

```powershell
scoop update openehr-explorer
```

## Note on SmartScreen

Releases aren't Authenticode-signed yet. Windows SmartScreen may warn on first launch — click "More info" → "Run anyway". Tracked in [openehr-explorer#OEH-5](https://github.com/platzhersh/openehr-explorer).

## Maintenance

`bucket/openehr-explorer.json` is kept in sync automatically by a workflow in the main repo (`.github/workflows/scoop-bucket.yml`), which runs on every `v*` release tag.
