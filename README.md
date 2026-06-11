# Lux Report

Static publish site for the report:

- Entry: `index.html`
- Source: `/Users/hj/Documents/立势工作/与AI同行/产品/硅基智能体_完整版.html`

GitHub Pages can publish this repository directly from the root directory.

## Sync

Run from the repository root after the canonical local HTML changes:

```sh
ruby scripts/sync_report.rb
git status --short
```

The sync script rewrites local image references into `images/` and fails if any
published image path escapes the repository.
