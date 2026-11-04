# plugin-webhook-notifier

Replacearr plugin: **webhook-notifier**.

Install from the curated marketplace, or paste this repo URL in **Plugins → Marketplace**.

## Develop

```bash
CGO_ENABLED=0 go build -o webhook-notifier .
```

## Release

```bash
git tag vX.Y.Z && git push --tags
```

CI uploads platform binaries and a release `plugin.json` (with sha256 assets) to the GitHub Release.
