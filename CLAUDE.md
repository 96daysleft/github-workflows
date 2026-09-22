# Workflow Naming Convention

All GitHub Actions workflow files must be named:

```
<what>-<action>.yml
```

- `<what>`: the subject/technology, e.g. `docker`, `python`, `javascript`, `node`, `helm`, `vscode-ext`, `action`.
- `<action>`: what the workflow does, e.g. `build`, `deploy`, `publish`, `release`, `release-tag`, `pr-check`.

Examples: `docker-build-push.yml`, `python-pr-check.yml`, `vscode-ext-publish.yml`, `helm-publish.yml`.

Also name the `name:` field inside each workflow file to match its filename (without the `.yml` extension).
