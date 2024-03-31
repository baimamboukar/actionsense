# Actionsense
A set of reusable `github actions` workflows.

<a href="#">
  <img src="https://skillicons.dev/icons?i=githubactions,github,flutter,dart,python&perline=8" alt="Skill Icons">
</a>

# Workflows
- [Flutter](#flutter)
- [Python](#python)
- [Dart](#dart)


## Flutter

### 1. Format and Analyze

```yaml
jobs:
  python:
    uses: baimamboukar/actionsense/.github/workflows/flutterformat.yaml@main
    with:
      flutter-version: 'latest'
      disable-test: false
```