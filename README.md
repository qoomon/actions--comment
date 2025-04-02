# Create GitHub Issue Comment &nbsp; [![Actions](https://img.shields.io/badge/qoomon-GitHub%20Actions-blue)](https://github.com/qoomon/actions)

# Inputs
- `content` comment content

### Example
```yaml
jobs:
  example:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4

      - uses: qoomon/actions--create-comment@v1
        with:
          issue: 42
          conntent: Hello World!
```

## Development

### Release New Action Version

Trigger [Release Version workflow](/actions/workflows/action-release.yaml)
